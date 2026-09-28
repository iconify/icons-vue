<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ulw2vbb9k"/><path class="poe4b57lm"/><path class="t0g-0_b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-arch-opened" /></template>
<style>
.poe4b57lm {
  fill: var(--svg-color--7f7adc, #7f7adc);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.t0g-0_b7i {
  fill: var(--svg-color--1793d1, #1793d1);
  fill-rule: evenodd;
  d: path("M21 11c-.89 2.18-1.43 3.61-2.42 5.73c.608.644 1.35 1.39 2.57 2.24c-1.3-.536-2.19-1.07-2.85-1.63c-1.27 2.65-3.26 6.42-7.29 13.7c3.17-1.83 5.63-2.96 7.92-3.39a5.8 5.8 0 0 1-.15-1.36l.004-.102c.05-2.03 1.11-3.59 2.36-3.49c1.25.106 2.22 1.84 2.17 3.87a6 6 0 0 1-.128 1.09c2.27.443 4.7 1.57 7.82 3.37c-.617-1.14-1.17-2.16-1.69-3.13c-.828-.642-1.69-1.48-3.45-2.38c1.21.315 2.08.678 2.75 1.08c-5.34-9.95-5.78-11.3-7.61-15.6z");
}

.ulw2vbb9k {
  fill: var(--svg-color--7f7adc, #7f7adc);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

</style>
