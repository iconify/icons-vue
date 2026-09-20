<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtilumbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airport-shuttle-rounded" /></template>
<style>
.gtilumbbg {
  fill: currentColor;
  d: path("M4.817 16.553q-.644-.64-.644-1.553h-.308q-.666 0-1.14-.475t-.475-1.14V7.623q0-.679.475-1.151Q3.199 6 3.864 6h11.83q.311 0 .594.115t.497.326l4.466 4.196q.237.217.367.524t.131.645v1.579q0 .666-.475 1.14t-1.14.475q0 .914-.644 1.553q-.645.64-1.549.64t-1.548-.64T15.749 15H8.558q0 .904-.644 1.548t-1.548.644t-1.549-.639m9.433-5.976h5.462l-3.635-3.404q-.096-.077-.202-.125T15.654 7H14.25zm-5.5 0h4.5V7h-4.5zm-5.5 0h4.5V7H3.866q-.27 0-.443.173t-.173.443zm4.003 5.31q.363-.362.363-.887t-.363-.887t-.888-.363t-.887.363t-.363.887t.363.888t.888.362t.887-.363m11.577 0q.362-.362.362-.887t-.362-.888t-.888-.362t-.887.363t-.363.887t.363.888t.887.362t.888-.363");
}

</style>
