<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy76dkb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-greater-than" /></template>
<style>
.dy76dkb7p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.5 17.5l8.25-5.5L6.5 6.5l1-1.5L18 12L7.5 19z");
}

</style>
