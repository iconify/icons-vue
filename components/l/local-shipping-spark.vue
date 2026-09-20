<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqt2v1poc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-shipping-spark" /></template>
<style>
.iqt2v1poc {
  fill: currentColor;
  d: path("M6.838 17.645q.47-.47.47-1.145t-.47-1.145t-1.146-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.146-.47m12.384 0q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.145-.47M16.538 13.5h4.712l-2.942-3.884h-1.77zM6.596 9.692q-.15 0-.2-.15q-.361-1.39-1.358-2.387T2.65 5.796q-.15-.05-.15-.2q0-.169.15-.2q1.39-.355 2.388-1.355T6.396 1.65q.05-.15.2-.15q.17 0 .2.15q.362 1.39 1.359 2.388q.997.997 2.387 1.358q.15.025.15.2q0 .15-.15.2q-1.39.362-2.387 1.359T6.796 9.542q-.025.15-.2.15m-2.76 8.664q-.759-.76-.759-1.856H1.692V9.79q.92 1.068 2.198 1.677q1.277.61 2.706.61q2.675 0 4.578-1.9t1.903-4.58q0-.145-.009-.299T13.037 5h3.502v3.616h2.307l3.462 4.653V16.5h-1.616q0 1.096-.76 1.856q-.759.76-1.855.76t-1.856-.76t-.76-1.856H8.308q0 1.096-.76 1.856t-1.856.76t-1.856-.76");
}

</style>
