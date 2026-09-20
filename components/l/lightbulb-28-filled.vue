<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gga3sfj4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-28-filled" /></template>
<style>
.gga3sfj4k {
  fill: currentColor;
  d: path("M14 2a9 9 0 0 0-5.79 15.89c.402.339.679.736.78 1.158l.35 1.452h9.322l.349-1.452c.101-.422.378-.819.78-1.158A9 9 0 0 0 14 2m4.301 20H9.7l.362 1.508A3.25 3.25 0 0 0 13.22 26h1.558a3.25 3.25 0 0 0 3.16-2.492z");
}

</style>
