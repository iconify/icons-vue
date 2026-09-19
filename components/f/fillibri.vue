<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hqc1lrnns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fillibri" /></template>
<style>
.hqc1lrnns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.211 12.566H25.843s.812-4.613 3.908-4.613l12.749.022c-3.613 1.878-4.29 4.59-4.29 4.59zM5.5 17.097h31.828l-.83 4.666H8.864s-3.363-.8-3.363-4.666zm8.014 9.195h22.198l-.797 4.666H16.877s-3.364-.8-3.364-4.666zm8.089 9.198h12.55s-.812 4.612-3.908 4.612H20.56z");
}

</style>
