<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k8r9c1jac"/><ellipse transform="rotate(-45.001 46.998 46.997)" class="u8d77ac9o"/><path class="mz1bedcjn"/><ellipse transform="rotate(-45.001 30.91 30.911)" class="yul_c0bcj"/><path class="opg5qbc5a"/><ellipse transform="rotate(-45.001 14.822 14.824)" class="ak3tzpbyr"/><path class="r6y-ecc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:dango" /></template>
<style>
.ak3tzpbyr {
  cx: 14.8px;
  cy: 14.8px;
  fill: var(--svg-color--ff99ad, #ff99ad);
  rx: 13.6px;
  ry: 12px;
}

.k8r9c1jac {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M50.9 48.6c-.6-.6-1.7-.6-2.3 0s-.6 1.7 0 2.3l10.6 10.6c.6.6 1.7.6 2.3 0s.6-1.7 0-2.3z");
}

.mz1bedcjn {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M38.3 35.9c-.6-.6-1.7-.6-2.3 0s-.6 1.7 0 2.3l3.7 3.7c.6.6 1.7.6 2.3 0s.6-1.7 0-2.3z");
}

.opg5qbc5a {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M22.2 19.9c-.6-.6-1.7-.6-2.3 0s-.6 1.7 0 2.3l3.7 3.7c.6.6 1.7.6 2.3 0s.6-1.7 0-2.3z");
}

.r6y-ecc2c {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M6.1 3.8c-.6-.6-1.7-.6-2.3 0s-.6 1.7 0 2.3l3.7 3.7c.6.6 1.7.6 2.3 0s.6-1.7 0-2.3z");
}

.u8d77ac9o {
  cx: 47px;
  cy: 47px;
  fill: var(--svg-color--8cc63e, #8cc63e);
  rx: 13.6px;
  ry: 12px;
}

.yul_c0bcj {
  cx: 30.9px;
  cy: 30.9px;
  fill: var(--svg-color--dae3ea, #dae3ea);
  rx: 13.6px;
  ry: 12px;
}

</style>
