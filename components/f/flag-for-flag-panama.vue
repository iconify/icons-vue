<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bef3uyb4h"/><path class="onjo0-ber"/><path class="xniqjrb5j"/><path class="johtb36pp"/><path class="i1aqzux1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-panama" /></template>
<style>
.bef3uyb4h {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2v30h30C62 15.4 48.6 2 32 2");
}

.i1aqzux1g {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("m47 46.7l3.1 2.3l-1.2-3.8l3.1-2.4h-3.8L47 39l-1.2 3.8H42l3.1 2.4l-1.2 3.8z");
}

.johtb36pp {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("m17 20.7l3.1 2.3l-1.2-3.8l3.1-2.4h-3.8L17 13l-1.2 3.8H12l3.1 2.4l-1.2 3.8z");
}

.onjo0-ber {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 62V32H2c0 16.6 13.4 30 30 30");
}

.xniqjrb5j {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 62V32h30c0 16.6-13.4 30-30 30m0-60v30H2C2 15.4 15.4 2 32 2");
}

</style>
