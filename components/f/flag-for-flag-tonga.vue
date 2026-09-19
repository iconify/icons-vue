<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ipeqx8bjf"/><g class="lqb-76dif"><path class="u8jxynxhr"/><path class="bq4kq2bel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-tonga" /></template>
<style>
.bq4kq2bel {
  d: path("M22 18h-5v-5h-4v5H8v4h5v5h4v-5h5z");
}

.ipeqx8bjf {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M26 2.6C12.3 5.4 2 17.5 2 32h24z");
}

.lqb-76dif {
  fill: var(--svg-color--c94747, #c94747);
}

.u8jxynxhr {
  d: path("M32 2q-3.15 0-6 .6V32H2c0 16.6 13.4 30 30 30s30-13.4 30-30S48.6 2 32 2");
}

</style>
