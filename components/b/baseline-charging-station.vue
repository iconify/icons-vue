<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt95n2j-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-charging-station" /></template>
<style>
.pt95n2j-s {
  fill: currentColor;
  d: path("m14.5 11l-3 6v-4h-2l3-6v4zM7 1h10c1.1 0 2 .9 2 2v18c0 1.1-.9 2-2 2H7c-1.1 0-2-.9-2-2V3c0-1.1.9-2 2-2m0 5v12h10V6z");
}

</style>
