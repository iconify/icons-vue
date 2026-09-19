<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xyhf222dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flash" /></template>
<style>
.xyhf222dv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.724 13.75L34.652 3.5l-8.785 13.179h2.928l-7.321 10.25h5.857L21.474 44.5L33.188 24h-5.125l6.589-10.25zm-17.693 20.1l3.377-21.32c.406-2.56 2.81-4.637 5.372-4.637h.901m-10.333 8.761h8.946");
}

</style>
