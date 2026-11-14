<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn7m2hbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flat-lay" /></template>
<style>
.xn7m2hbzu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 1.75H6q-1.76 0-3.005 1.245T1.75 6v12q0 1.76 1.245 3.005T6 22.25h12q1.76 0 3.005-1.245T22.25 18V6q0-1.76-1.245-3.005T18 1.75m-10.75 3h4.5q2.5 0 2.5 2.5v1q0 2.391-2.287 2.495q.037.234.037.505q0 2-2 2H9q-2 0-2-2q0-.271.037-.505Q4.75 10.641 4.75 8.25v-1q0-2.5 2.5-2.5M12.75 16q0-3.25 3.25-3.25T19.25 16T16 19.25T12.75 16");
}

</style>
