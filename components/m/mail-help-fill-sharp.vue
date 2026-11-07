<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djpfmrb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-help-fill-sharp" /></template>
<style>
.djpfmrb3z {
  fill: currentColor;
  d: path("M15.236 3.832A3 3 0 1 1 18 8a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 17 5a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M13.432 10H9.414l-6-6H11a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779A6 6 0 0 0 13.432 10M4 7.414l4.293 4.293A1 1 0 0 0 9 12h6c.26 0 .51-.102.697-.283c.981.489 2.083.778 3.184.739a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5.414ZM18.01 9a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

</style>
