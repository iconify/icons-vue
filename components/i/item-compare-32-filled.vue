<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="etccwp0iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:item-compare-32-filled" /></template>
<style>
.etccwp0iq {
  fill: currentColor;
  d: path("M16 3a1 1 0 0 1 1 1v24a1 1 0 1 1-2 0V4a1 1 0 0 1 1-1m-6.25 7A3.25 3.25 0 0 1 13 13.25v5.5A3.25 3.25 0 0 1 9.75 22h-5.5A3.25 3.25 0 0 1 1 18.75v-5.5A3.25 3.25 0 0 1 4.25 10zm18 0A3.25 3.25 0 0 1 31 13.25v5.5A3.25 3.25 0 0 1 27.75 22h-5.5A3.25 3.25 0 0 1 19 18.75v-5.5A3.25 3.25 0 0 1 22.25 10z");
}

</style>
