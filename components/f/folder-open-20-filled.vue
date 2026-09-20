<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x5-xq-b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-open-20-filled" /></template>
<style>
.x5-xq-b1f {
  fill: currentColor;
  d: path("M4.5 3A2.5 2.5 0 0 0 2 5.5v6.971l1.568-2.716A3.5 3.5 0 0 1 6.6 8.005H16V7.5A2.5 2.5 0 0 0 13.5 5H9.707l-1.56-1.56A1.5 1.5 0 0 0 7.085 3zm-.066 7.255A2.5 2.5 0 0 1 6.6 9.005h10.396c1.54 0 2.502 1.666 1.732 3l-2.162 3.745A2.5 2.5 0 0 1 14.4 17H4.004c-1.54 0-2.502-1.667-1.732-3z");
}

</style>
