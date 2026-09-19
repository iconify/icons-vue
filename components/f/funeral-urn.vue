<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNgffFc)" class="jc1-gz67z"/><path fill="url(#iijcEme)" class="zc483sa4w"/><path fill="url(#i0wowib)" clip-rule="evenodd" class="b8-ah3mav"/><defs><radialGradient id="iNgffFc" cx="0" cy="0" r="1" gradientTransform="matrix(-3 6 -12 -5.99999 18 3.5)" gradientUnits="userSpaceOnUse"><stop class="w9buxfbzy"/><stop offset="1" class="r5x-dlr_f"/></radialGradient><radialGradient id="iijcEme" cx="0" cy="0" r="1" gradientTransform="matrix(-5.92854 16.57143 -20.23768 -7.24016 19.429 11.929)" gradientUnits="userSpaceOnUse"><stop class="w9buxfbzy"/><stop offset="1" class="r5x-dlr_f"/></radialGradient><linearGradient id="i0wowib" x1="3.5" x2="22.5" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="i2qyqrbov"/><stop offset="1" class="r5x-dlr_f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:funeral-urn" /></template>
<style>
.b8-ah3mav {
  fill-rule: evenodd;
  d: path("M27.97 13a12 12 0 0 0-.278-2H4.308a12 12 0 0 0-.279 2zM4.026 15q.051 1.021.192 2h23.566c.093-.652.16-1.32.192-2z");
}

.ft5dv1b6b {
  fill: none;
}

.i2qyqrbov {
  stop-color: var(--svg-color--7d4533, #7D4533);
}

.jc1-gz67z {
  d: path("M16 2a7 7 0 0 0-7 7h14a7 7 0 0 0-7-7");
}

.r5x-dlr_f {
  stop-color: var(--svg-color--a56953, #A56953);
}

.w9buxfbzy {
  stop-color: var(--svg-color--f3ad61, #F3AD61);
}

.zc483sa4w {
  d: path("M4 14c0-7 4-7 4-7h16s4 0 4 7c0 6.538-3.167 12.021-4.899 14.531c-.663.961-1.773 1.469-2.94 1.469H11.84c-1.168 0-2.278-.508-2.941-1.469C7.167 26.021 4 20.538 4 14");
}

</style>
