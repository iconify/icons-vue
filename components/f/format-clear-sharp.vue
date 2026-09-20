<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu2w2hnat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-clear-sharp" /></template>
<style>
.pu2w2hnat {
  fill: currentColor;
  d: path("m13.2 10.35l-2.325-2.325L7.85 5H20v3h-5.8zm6.6 12.25l-8.3-8.3l-2 4.7H6.225L9.2 12L1.4 4.2l1.4-1.4l18.4 18.4z");
}

</style>
