<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ga4hcwl2q"/><circle class="kz23bi-bq"/><path class="w_juc4w8c"/><path class="ftuq662rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:computer-disk" /></template>
<style>
.ftuq662rw {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M38.4 24c-3.5 0-6.4 2.9-6.4 6.4v3.2c0 3.5 2.9 6.4 6.4 6.4H64V24z");
}

.ga4hcwl2q {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M64 57.6c0 3.5-2.9 6.4-6.4 6.4H6.4C2.9 64 0 61.1 0 57.6V6.4C0 2.9 2.9 0 6.4 0h51.2C61.1 0 64 2.9 64 6.4z");
}

.kz23bi-bq {
  cx: 32px;
  cy: 32px;
  r: 32px;
  fill: var(--svg-color--42ade2, #42ade2);
}

.w_juc4w8c {
  fill: var(--svg-color--fff, #fff);
  d: path("M32 40.4c-4.6 0-8.4-3.8-8.4-8.4s3.8-8.4 8.4-8.4s8.4 3.8 8.4 8.4s-3.8 8.4-8.4 8.4");
}

</style>
