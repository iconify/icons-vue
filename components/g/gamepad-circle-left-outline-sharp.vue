<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpp6qwg-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gamepad-circle-left-outline-sharp" /></template>
<style>
.tpp6qwg-i {
  fill: currentColor;
  d: path("M3.92 14.235Q3 13.315 3 12t.92-2.234t2.234-.92t2.235.92q.919.918.919 2.234t-.92 2.235t-2.234.919t-2.235-.92m11.693 0q-.92-.918-.92-2.234t.92-2.234q.919-.92 2.234-.92q1.316 0 2.235.92Q21 10.683 21 12t-.92 2.235q-.919.919-2.234.919t-2.235-.92m3.76-.708Q20 12.9 20 12.002t-.628-1.526t-1.524-.63t-1.526.628t-.63 1.524t.628 1.526t1.524.63t1.526-.628M9.766 8.384q-.92-.923-.92-2.23t.92-2.23T12 3t2.235.924q.919.923.919 2.23t-.92 2.23q-.918.924-2.234.924t-2.234-.924m3.758-.704q.63-.627.63-1.524t-.628-1.526T12.002 4t-1.526.628t-.63 1.524t.628 1.526t1.524.63t1.526-.628M9.766 20.07q-.92-.929-.92-2.244q0-1.314.92-2.224q.919-.91 2.234-.91t2.235.91t.919 2.224t-.92 2.245Q13.317 21 12 21t-2.234-.93m3.758-.71q.63-.639.63-1.53q0-.89-.628-1.514q-.627-.624-1.524-.624t-1.526.624t-.63 1.514t.628 1.53t1.524.64t1.526-.64");
}

</style>
