<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uupvhfbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bike-dock-outline-sharp" /></template>
<style>
.uupvhfbwl {
  fill: currentColor;
  d: path("M3 21v-2l4.25-1.225L9 3h6l1.75 14.775L21 19v2zm8-3h2V5h-2z");
}

</style>
