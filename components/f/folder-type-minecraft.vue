<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r7ky9zbbc"/><path class="tipeoubwm"/><path class="h_la5obvj"/><path class="e8j06tb6s"/><path class="ioi3ou6ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-minecraft" /></template>
<style>
.e8j06tb6s {
  d: path("M26.5 18.65v-3.81h-3.82v3.81h-3.81v1.9h-1.9v5.73h1.9v-1.9h3.81v1.9h1.9v-5.72h-1.9v-1.9h3.81m-7.62-3.82h-3.82v3.81h3.82z");
}

.h_la5obvj {
  fill: var(--svg-color--86d562, #86d562);
  d: path("M26.5 18.65h-3.82v.32h3.81v-.32m-3.8 5.72h-3.82v.32h3.81v-.32m1.9 1.9h-1.9v.33h1.9v-.32m-5.71 0h-1.9v.32h1.9zm0-7.63h-3.82v.32h3.82z");
}

.ioi3ou6ew {
  fill: var(--svg-color--2a641c, #2a641c);
  d: path("M26.5 14.84h-3.82v.32h3.81v-.32m-3.8 3.81h-3.82v.32h3.81v-.32m-3.81-3.81h-3.82v.32h3.82zm0 5.72h-1.9v.32h1.9zm5.72 0h-1.9v.32h1.9z");
}

.r7ky9zbbc {
  fill: var(--svg-color--2a641c, #2a641c);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.tipeoubwm {
  fill: var(--svg-color--52a535, #52a535);
  d: path("M30.3 11.02H11.25V30.1h19.07z");
}

</style>
