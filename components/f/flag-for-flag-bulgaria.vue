<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i2b6d14ke"/><path class="pk07sfbhl"/><path class="r6w68ib0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-bulgaria" /></template>
<style>
.i2b6d14ke {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

.pk07sfbhl {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.r6w68ib0a {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

</style>
