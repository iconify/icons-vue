<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x--qt6c_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-mac" /></template>
<style>
.x--qt6c_a {
  fill: currentColor;
  d: path("M9.27 20v-.77l1.884-1.884H4.616q-.691 0-1.153-.462T3 15.73V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616V15.73q0 .69-.463 1.153t-1.153.462h-6.538l1.885 1.885V20z");
}

</style>
