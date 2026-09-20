<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbz_gwbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:floor" /></template>
<style>
.rbz_gwbjy {
  fill: currentColor;
  d: path("M3.5 21.5v-1H7V16h4.5v-4.5H16V7h4.5V3.5h1V8H17v4.5h-4.5V17H8v4.5z");
}

</style>
