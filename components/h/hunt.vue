<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhfftb-ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hunt" /></template>
<style>
.qhfftb-ib {
  fill: var(--svg-color--fb6f6e, #fb6f6e);
  d: path("M7.372 4.029a1.028 1.028 0 1 1 2.057 0V8.41a4.628 4.628 0 0 1 7.2 3.847v4.629a1.029 1.029 0 0 1-2.057 0v-4.629a2.571 2.571 0 0 0-5.143 0v4.629a1.029 1.029 0 0 1-2.057 0zM9.429 19.97a1.029 1.029 0 1 1-2.058 0a1.029 1.029 0 0 1 2.058 0M15.6 21a1.029 1.029 0 1 0 0-2.057a1.029 1.029 0 0 0 0 2.057");
}

</style>
