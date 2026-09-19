<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s0s4ymbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cflumen" /></template>
<style>
.s0s4ymbpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.5 24A21.49 21.49 0 0 1 32 4.055a21.5 21.5 0 1 0 0 39.89A21.49 21.49 0 0 1 18.5 24m20.326-6.674l2.36 4.314L45.5 24l-4.314 2.36l-2.36 4.314l-2.359-4.314L32.152 24l4.315-2.36z");
}

</style>
