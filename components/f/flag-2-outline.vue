<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz9g9ubfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flag-2-outline" /></template>
<style>
.nz9g9ubfk {
  fill: currentColor;
  d: path("M5 22V3h16l-2 5l2 5H7v9zm2-11h11.05l-1.2-3l1.2-3H7zm0 0V5z");
}

</style>
