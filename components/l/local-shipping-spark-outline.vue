<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giyhsnbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-shipping-spark-outline" /></template>
<style>
.giyhsnbwf {
  fill: currentColor;
  d: path("M6.838 17.645q.47-.47.47-1.145t-.47-1.145t-1.146-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.146-.47m12.384 0q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.145-.47M16.538 13.5h4.712l-2.942-3.884h-1.77zm-3.5-8.5h3.502v3.616h2.307l3.462 4.653V16.5h-1.616q0 1.09-.764 1.853t-1.855.762t-1.852-.762t-.76-1.853H8.309q0 1.096-.764 1.856t-1.856.76t-1.852-.763t-.759-1.853H1.692V9.79q.233.252.474.472t.526.411V15.5h.647q.213-.662.869-1.138t1.484-.478q.79 0 1.466.468q.675.467.888 1.148h7.493V6H13.07q.031-.25.013-.5t-.048-.5m-6.44 4.692q-.15 0-.2-.15q-.361-1.39-1.358-2.387T2.65 5.796q-.15-.05-.15-.2q0-.169.15-.2q1.39-.355 2.388-1.355T6.396 1.65q.05-.15.2-.15q.17 0 .2.15q.362 1.39 1.359 2.388q.997.997 2.387 1.358q.15.025.15.2q0 .15-.15.2q-1.39.362-2.387 1.359T6.796 9.542q-.025.15-.2.15");
}

</style>
