<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr205w_yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:general-device-outline-sharp" /></template>
<style>
.cr205w_yt {
  fill: currentColor;
  d: path("M8 18V3h8v15zm2-2h4V5h-4zm-2 5v-2h8v2zm2-5h4z");
}

</style>
