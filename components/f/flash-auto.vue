<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqz7hr6ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flash-auto" /></template>
<style>
.uqz7hr6ov {
  fill: currentColor;
  d: path("M5 22v-8H2V2h10l-2 7h4zm9.625-11L18 2h1.6l3.425 9h-1.55l-.8-2.3h-3.7l-.8 2.3zm2.8-3.6h2.75L18.85 3.65h-.05z");
}

</style>
