<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-qenbb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:fast-forward" /></template>
<style>
.t-qenbb4q {
  fill: currentColor;
  d: path("m4 18l8.5-6L4 6zm9-12v12l8.5-6z");
}

</style>
