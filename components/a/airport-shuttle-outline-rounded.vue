<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygkxo5b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airport-shuttle-outline-rounded" /></template>
<style>
.ygkxo5b2h {
  fill: currentColor;
  d: path("M4.817 16.553q-.644-.64-.644-1.553h-.308q-.666 0-1.14-.475t-.475-1.14V7.623q0-.679.475-1.151Q3.199 6 3.864 6h11.83q.311 0 .594.115t.497.326l4.466 4.196q.237.217.367.524t.131.645v1.579q0 .666-.475 1.14t-1.14.475q0 .914-.644 1.553q-.645.64-1.549.64t-1.548-.64T15.749 15H8.558q0 .904-.644 1.548t-1.548.644t-1.549-.639m9.433-5.976h5.462l-3.635-3.404q-.096-.077-.202-.125T15.654 7H14.25zm-5.5 0h4.5V7h-4.5zm-5.5 0h4.5V7H3.866q-.27 0-.443.173t-.173.443zm4.003 5.31q.363-.362.363-.887t-.363-.887t-.888-.363t-.887.363t-.363.887t.363.888t.888.362t.887-.363m11.577 0q.362-.362.362-.887t-.362-.888t-.888-.362t-.887.363t-.363.887t.363.888t.887.362t.888-.363M8.296 14h7.716q.213-.45.734-.821t1.196-.371t1.168.342t.763.85h.262q.269 0 .442-.173t.173-.442v-1.808H3.25v1.808q0 .269.173.442t.443.173h.568q.214-.45.735-.821q.522-.371 1.197-.371t1.167.342t.763.85m12.454-2.423H3.25z");
}

</style>
