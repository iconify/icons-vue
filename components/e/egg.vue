<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="d_wk_qbvx"/><path fill="url(#itx3hIN)" class="am7z200-h"/><path fill="url(#icY9Jbz)" class="am7z200-h"/><defs><radialGradient id="itx3hIN" cx="0" cy="0" r="1" gradientTransform="rotate(89.708 6.161 16.62)scale(24.5003 16.2938)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="ebgkdcb0b"/><stop offset=".562" class="cihuz7ius"/><stop offset=".838" class="axpha8bfr"/><stop offset="1" class="fc220vm1r"/></radialGradient><radialGradient id="icY9Jbz" cx="0" cy="0" r="1" gradientTransform="rotate(97.431 3.208 12.778)scale(22.5645 27.4892)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="ptuq24e9e"/><stop offset=".904" class="fj8gb4bke"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:egg" /></template>
<style>
.am7z200-h {
  d: path("M16.331 2c-2.57 0-4.98 1.28-6.42 3.4l-.13.19A21.92 21.92 0 0 0 6.101 20l.08.8c.5 5.21 4.88 9.18 10.11 9.18c5.25 0 9.63-3.99 10.11-9.22l.09-.93a21.9 21.9 0 0 0-3.78-14.48A7.77 7.77 0 0 0 16.331 2");
}

.axpha8bfr {
  stop-color: var(--svg-color--b87241, #B87241);
}

.cihuz7ius {
  stop-color: var(--svg-color--e5945b, #E5945B);
}

.d_wk_qbvx {
  fill: var(--svg-color--a6704c, #A6704C);
  d: path("M16.331 2c-2.57 0-4.98 1.28-6.42 3.4l-.13.19A21.92 21.92 0 0 0 6.101 20l.08.8c.5 5.21 4.88 9.18 10.11 9.18c5.25 0 9.63-3.99 10.11-9.22l.09-.93a21.9 21.9 0 0 0-3.78-14.48A7.77 7.77 0 0 0 16.331 2");
}

.ebgkdcb0b {
  stop-color: var(--svg-color--ffca7f, #FFCA7F);
}

.fc220vm1r {
  stop-color: var(--svg-color--9a6240, #9A6240);
}

.fj8gb4bke {
  stop-color: var(--svg-color--984663, #984663);
}

.ft5dv1b6b {
  fill: none;
}

.ptuq24e9e {
  stop-color: var(--svg-color--974668, #974668);
  stop-opacity: 0;
}

</style>
