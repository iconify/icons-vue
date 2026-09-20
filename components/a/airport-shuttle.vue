<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6cbfmb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airport-shuttle" /></template>
<style>
.v6cbfmb3m {
  fill: currentColor;
  d: path("M4.817 16.553q-.644-.64-.644-1.553H2.25V7q0-.413.294-.706T3.25 6h13.077l5.423 5.116V15h-1.616q0 .914-.639 1.553q-.64.64-1.553.64t-1.553-.64q-.639-.64-.639-1.553H8.558q0 .904-.644 1.548t-1.548.644t-1.549-.639m9.433-5.976h5.462L15.904 7H14.25zm-5.5 0h4.5V7h-4.5zm-5.5 0h4.5V7h-4.5zm4.003 5.31q.363-.362.363-.887t-.363-.887t-.888-.363t-.887.363t-.363.887t.363.888t.888.362t.887-.363m11.577 0q.362-.362.362-.887t-.362-.888t-.888-.362t-.887.363t-.363.887t.363.888t.887.362t.888-.363");
}

</style>
