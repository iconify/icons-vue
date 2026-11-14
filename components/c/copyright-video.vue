<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guyh0vbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:copyright-video" /></template>
<style>
.guyh0vbez {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 4.25H6.875q-2.123 0-3.624 1.501T1.75 9.375v5.25q0 2.123 1.501 3.624t3.624 1.501h6.772q-.147-.595-.147-1.25q0-2.071 1.464-3.536Q16.429 13.5 18.5 13.5t3.536 1.464q.098.098.189.199q.025-.264.025-.538v-5.25q0-2.123-1.501-3.624T17.125 4.25m-4.467 5.47l.584.351q1.092.656 1.092 1.929t-1.092 1.929l-.584.351q-1.125.675-2.266.029T9.25 12.351v-.702q0-1.312 1.142-1.958t2.266.029m2.092 8.78q0-3.75 3.75-3.75t3.75 3.75t-3.75 3.75t-3.75-3.75m1.5 0q0 2.25 2.25 2.25t2.25-2.25t-2.25-2.25t-2.25 2.25m2.655.948q-.176.052-.405.052q-1 0-1-1t1-1t1 1q0 .674-.455.894q-.069.028-.14.054");
}

</style>
