<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="yvb0blvjs"/><path class="io9k0vbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-switzerland" /></template>
<style>
.io9k0vbeq {
  fill: var(--svg-color--fff, #fff);
  d: path("M47 27H37V17H27v10H17v10h10v10h10V37h10z");
}

.yvb0blvjs {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

</style>
