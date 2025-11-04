<script setup>

</script>

<template>
    <section class="meal-plan">
        <header class="meal-plan__header">
            <h1 class="meal-plan__title">
                Weekly meal plan
            </h1>

            <p class="meal-plan__subtitle">
                Plan breakfasts lunches dinners and snacks for seven days
            </p>

            <nav class="meal-plan__week-nav">
            </nav>
        </header>

        <section class="meal-plan__targets">
            <h2 class="meal-plan__targets-title">
                Weekly targets
            </h2>

            <div class="meal-plan__target-group">
                calories label and value placeholders
            </div>

            <div class="meal-plan__target-group">
                proteins label and value placeholders
            </div>

            <div class="meal-plan__target-group">
                carbs label and value placeholders
            </div>

            <div class="meal-plan__target-group">
                fats label and value placeholders
            </div>
        </section>

        <section class="meal-plan__week">
            <h2 class="meal-plan__week-title">
                This week
            </h2>

            <div class="meal-plan__week-days">
                weekdays labels
                <div class="meal-plan__week-day data-day">
                    Mon
                </div>

                <div class="meal-plan__week-day data-day">
                    Tue
                </div>

                <div class="meal-plan__week-day data-day">
                    Wed
                </div>

                <div class="meal-plan__week-day data-day">
                    Thu
                </div>

                <div class="meal-plan__week-day data-day">
                    Fri
                </div>

                <div class="meal-plan__week-day data-day">
                    Sat
                </div>

                <div class="meal-plan__week-day data-day">
                    Sun
                </div>
            </div>

            <div class="meal-plan__days">
                <article class="meal-plan__day">
                    for day one
                    <header class="meal-plan__day-header">
                        <span class="meal-plan__day-name">
                            Mon
                        </span>

                        <span class="meal-plan__day-date">
                            01
                        </span>
                    </header>

                    <div class="meal-plan__meals">
                        <section class="meal-plan__meal-block meal-plan__meal-block-breakfast">
                            <div></div>
                            <h3 class="meal-plan__meal-title">
                                Breakfast
                            </h3>

                            <div class="meal-plan__meal-list">
                                No items yet
                            </div>
                        </section>

                        <section class="meal-plan__meal-block meal-plan__meal-block-lunch">
                            <h3 class="meal-plan__meal-title">
                                Lunch
                            </h3>

                            <div class="meal-plan__meal-list">
                                No items yet
                            </div>
                        </section>

                        <section class="meal-plan__meal-block meal-plan__meal-block-dinner">
                            <h3 class="meal-plan__meal-title">
                                Dinner
                            </h3>

                            <div class="meal-plan__meal-list">
                                No items yet
                            </div>
                        </section>

                        <section class="meal-plan__meal-block meal-plan__meal-block-snack">
                            <h3 class="meal-plan__meal-title">
                                Snack
                            </h3>

                            <div class="meal-plan__meal-list">
                                No items yet
                            </div>
                        </section>
                    </div>

                    <footer class="meal-plan__day-footer">
                        for totals
                        <ul class="meal-plan__totals">
                            <li class="meal-plan__total-item meal-plan__total-item-calories">
                                Calories 0kcal
                            </li>

                            <li class="meal-plan__total-item meal-plan__total-item-protein">
                                Protein 0g
                            </li>

                            <li class="meal-plan__total-item meal-plan__total-item-carbs">
                                Carbs 0g
                            </li>

                            <li class="meal-plan__total-item meal-plan__total-item-fat">
                                Fat 0g
                            </li>
                        </ul>
                    </footer>
                </article>
            </div>
        </section>
    </section>
</template>

<style lang="scss" >
.meal-plan{
    &__days{
        display:grid;
        grid-template-columns: repeat(7, 1fr);
    }
}
</style>
