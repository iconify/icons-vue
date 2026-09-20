<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ify7fm_wv"/><path class="fj9slhqkf"/><path class="jp306acec"/><path class="r73d2ccdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-timor-leste" /></template>
<style>
.fj9slhqkf {
  fill: var(--svg-color--ffc726, #FFC726);
  d: path("M16 18L1.296 29.947c.079.072.16.141.244.207L23.667 18L1.54 5.846a4.037 4.037 0 0 0-.244.207L16 18z");
}

.ify7fm_wv {
  fill: var(--svg-color--dc241f, #DC241F);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

.jp306acec {
  fill: var(--svg-color--141414, #141414);
  d: path("M1.296 6.053l-.002.001A3.99 3.99 0 0 0 0 9v18c0 1.166.499 2.216 1.296 2.947L16 18L1.296 6.053z");
}

.r73d2ccdj {
  fill: var(--svg-color--fff, #FFF);
  d: path("M4.761 19.01l.492 3.269l1.523-2.934l3.262.542l-2.32-2.355l1.523-2.934l-2.957 1.478l-2.32-2.355l.493 3.269L1.5 18.468z");
}

</style>
