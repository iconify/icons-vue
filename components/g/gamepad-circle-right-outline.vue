<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w28bfup0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gamepad-circle-right-outline" /></template>
<style>
.w28bfup0l {
  fill: currentColor;
  d: path("M15.612 14.235q-.92-.92-.92-2.235t.92-2.234t2.234-.92t2.235.92T21 12t-.92 2.235q-.919.919-2.234.919t-2.235-.92m-11.692 0Q3 13.317 3 12t.92-2.234q.919-.92 2.234-.92t2.235.92T9.308 12t-.92 2.235t-2.234.919t-2.235-.92m3.759-.708q.63-.627.63-1.524t-.628-1.526t-1.524-.63t-1.526.628T4 11.998t.628 1.526t1.524.63t1.526-.628m2.088 6.55q-.92-.923-.92-2.23t.92-2.23T12 14.692t2.235.924t.919 2.23q0 1.307-.92 2.23Q13.317 21 12 21t-2.234-.923m3.758-.705q.63-.627.63-1.524t-.628-1.526t-1.524-.63t-1.526.628t-.63 1.524t.628 1.526t1.524.63t1.526-.628M9.766 8.398q-.92-.91-.92-2.224t.92-2.244T12 3t2.235.93t.919 2.244q0 1.314-.92 2.224q-.918.91-2.234.91t-2.234-.91m3.758-.714q.63-.624.63-1.514q0-.891-.628-1.53Q12.9 4 12.002 4t-1.526.64t-.63 1.53q0 .89.628 1.514q.627.624 1.524.624t1.526-.624");
}

</style>
