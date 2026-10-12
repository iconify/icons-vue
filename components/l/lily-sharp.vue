<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf0z4-bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lily-sharp" /></template>
<style>
.lf0z4-bal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.56 9.03l-2.27.94l-.69.28l.1.74l.32 2.43l.11.74l-.6-.46l-1.94-1.49l-.59-.46l-.59.46l-1.94 1.49l-.59.46l.1-.74l.32-2.43l.1-.74l-.69-.28l-2.27-.94l-.69-.28l.69-.28l2.27-.94l.69-.28l-.1-.74l-.32-2.43l-.11-.74l.6.46l1.94 1.49l.59.46l.59-.46l1.94-1.49l.6-.46l-.11.74l-.32 2.43l-.1.74l.69.28l2.27.94l.69.28zM12 8.75l1.75-3.03M12 8.75l1.75 3.03M12 8.75H8.5m3.5 3v9.5m0-.25c.75-3.25 3.5-5.25 7.5-5.25C19 19 16.25 21 12 21Z");
}

</style>
