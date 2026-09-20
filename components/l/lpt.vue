<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy4tk9w6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lpt" /></template>
<style>
.iy4tk9w6q {
  fill: var(--svg-color--00eb88, #00eb88);
  d: path("M7.2 3H3.6v3.6h3.6zm0 7.2H3.6v3.6h3.6zm-3.6 7.2h3.6V21H3.6zm10.201-3.6h-3.6v3.601h3.6zm-3.6-7.2h3.6v3.6h-3.6zm10.2 3.6h-3.6v3.6h3.6z");
}

</style>
