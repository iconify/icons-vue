<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="scuexhb4w"/><path class="t0y22zbdi"/><path class="cucjub_ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-qatar" /></template>
<style>
.cucjub_ro {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M2 32c0 11.3 6.3 21.1 15.5 26.3L28 56l-10-3l10-3l-10-3l10-3l-10-3l10-3l-10-3l10-3l-10-3l10-3l-10-3l10-3l-10-3l10-3l-10-3l10-3l-10.5-2.3C8.3 10.9 2 20.7 2 32");
}

.scuexhb4w {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M32 2c-5.3 0-10.2 1.4-14.5 3.7v52.5C21.8 60.6 26.7 62 32 62c16.6 0 30-13.4 30-30S48.6 2 32 2");
}

.t0y22zbdi {
  fill: var(--svg-color--9450e0, #9450e0);
  d: path("M32 2c-5.3 0-10.2 1.4-14.5 3.7v52.5C21.8 60.6 26.7 62 32 62c16.6 0 30-13.4 30-30S48.6 2 32 2");
  opacity: var(--svg-opacity--0-33, 0.33);
}

</style>
