<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xy6v266xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vscode3" /></template>
<style>
.xy6v266xn {
  fill: var(--svg-color--007acc, #007acc);
  d: path("M29.821 4.321L24.023 2l-12.53 12.212l-7.66-5.827l-1.654.837V22.8l1.644.827l7.65-5.827L24.023 30l5.8-2.321V4.321ZM4.65 19.192v-6.374l3.55 3.167zM16 15.985l7.082-5.3v10.639l-7.092-5.339z");
}

</style>
