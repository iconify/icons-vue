<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5t4cbc_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gamepad-circle-up-outline-rounded" /></template>
<style>
.c5t4cbc_b {
  fill: currentColor;
  d: path("M9.766 8.389q-.92-.92-.92-2.235t.92-2.235T12 3t2.235.92t.919 2.234t-.92 2.235T12 9.308t-2.234-.92m0 11.693q-.92-.92-.92-2.235t.92-2.234t2.234-.92t2.235.92t.919 2.234t-.92 2.235Q13.317 21 12 21t-2.234-.92m3.758-.707q.63-.628.63-1.525t-.628-1.526t-1.524-.63t-1.526.628t-.63 1.524t.628 1.526t1.524.63t1.526-.628m4.322-4.218q-1.306 0-2.23-.92q-.924-.919-.924-2.234t.924-2.235t2.23-.919t2.23.92Q21 10.683 21 12t-.923 2.235q-.924.919-2.23.919m-.003-1q.896 0 1.526-.628t.63-1.524t-.628-1.526t-1.524-.63t-1.526.628t-.63 1.524t.628 1.526t1.524.63m-11.67 1q-1.315 0-2.245-.92Q3 13.317 3 12t.93-2.234q.929-.92 2.244-.92q1.314 0 2.224.92q.91.918.91 2.234t-.91 2.235t-2.224.919m-.004-1q.89 0 1.514-.628q.624-.627.624-1.524t-.624-1.526t-1.514-.63t-1.53.628T4 11.998t.64 1.526t1.53.63");
}

</style>
