<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v1_kvphmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-arrow-down-16-filled" /></template>
<style>
.v1_kvphmc {
  fill: currentColor;
  d: path("M15 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4.854 2.353l.003.003a.5.5 0 0 0 .348.144h.006a.5.5 0 0 0 .35-.146l2-2a.5.5 0 0 0-.707-.708L11 6.293V3.5a.5.5 0 0 0-1 0v2.793L8.854 5.146a.5.5 0 1 0-.708.708zM10.5 11c1.33 0 2.55-.472 3.501-1.258v.755a1.5 1.5 0 0 1-1.5 1.5h-2.5V13h1.5a.5.5 0 1 1 0 1H4.495a.5.5 0 0 1 0-1H6v-1.003H3.501a1.5 1.5 0 0 1-1.5-1.5V3.5a1.5 1.5 0 0 1 1.5-1.5h2.756a5.5 5.5 0 0 0 4.243 9m-1.5.997H7V13h2z");
}

</style>
