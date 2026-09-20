<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jei84b-4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flip-camera-android-outline-rounded" /></template>
<style>
.jei84b-4g {
  fill: currentColor;
  d: path("M12 21.5q-3.008 0-5.435-1.7q-2.429-1.7-3.446-4.477q-.067-.221-.002-.421q.066-.2.273-.267q.208-.068.397.058t.263.348q.939 2.467 3.108 3.963T12 20.5q2.516 0 4.577-1.399t3.285-3.601H17q-.213 0-.357-.143T16.5 15t.143-.357T17 14.5h3.692q.349 0 .578.23t.23.578V19q0 .214-.143.357T21 19.5t-.357-.143T20.5 19v-2.654q-1.367 2.304-3.592 3.729T12 21.5m0-18q-2.516 0-4.577 1.399T4.138 8.5H7q.214 0 .357.143T7.5 9t-.143.357T7 9.5H3.308q-.348 0-.578-.23t-.23-.578V5q0-.213.143-.357T3 4.5t.357.143T3.5 5v2.654Q4.867 5.35 7.092 3.925T12 2.5q3.008 0 5.445 1.7T20.9 8.677q.067.221-.008.421t-.282.267t-.397-.058t-.263-.348q-.938-2.467-3.108-3.963T12 3.5m-1.423 9.923Q10 12.846 10 12t.577-1.423T12 10t1.423.577T14 12t-.577 1.423T12 14t-1.423-.577");
}

</style>
