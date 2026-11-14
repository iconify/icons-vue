<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s__-nkb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:give-way-sign" /></template>
<style>
.s__-nkb7c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.517 2.75H5.483q-1.432 0-2.157 1.235T3.3 6.47l6.517 11.662q.715 1.281 2.183 1.281t2.183-1.281L20.7 6.47q.699-1.25-.026-2.485T18.517 2.75m-8.412 3h3.79q1.301 0 1.95 1.127t-.004 2.253l-1.895 3.263q-.651 1.119-1.946 1.119t-1.945-1.119L8.159 9.13q-.653-1.125-.004-2.253q.649-1.127 1.95-1.127");
}

</style>
