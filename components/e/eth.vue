<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iysdmlc3u"/><path class="zowzdtb6j"/><path class="avc1f0b1m"/><path class="wanylc-wf"/><path class="vtekotdpj"/><path class="obb1rfb6z"/><path clip-rule="evenodd" class="jkoj7_w6c"/><path clip-rule="evenodd" class="co0vc0kck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eth" /></template>
<style>
.avc1f0b1m {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("M12 16.477v4.522l5.625-7.784z");
}

.co0vc0kck {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("M12 16.406L6.375 13.21L12 21l5.625-7.79zm-4.995-2.633l4.905 2.79v4.005zm5.085 2.79v4.005l4.905-6.795z");
}

.ft5dv1b6b {
  fill: none;
}

.iysdmlc3u {
  fill: var(--svg-color--8ffcf3, #8ffcf3);
  d: path("M12 3v6.65l5.625 2.516z");
}

.jkoj7_w6c {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("m12 15.429l-5.625-3.263L12 3l5.625 9.166zM6.749 11.9l5.16-8.41v6.115zm-.077.23l5.238-2.327v5.364zm5.418-2.327v5.364l5.233-3.038zm0-.198l5.16 2.295l-5.16-8.41z");
}

.obb1rfb6z {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("M6.375 12.167L12 15.429V9.651z");
}

.vtekotdpj {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("m12 15.43l5.625-3.263L12 9.65z");
}

.wanylc-wf {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("M12 21v-4.523l-5.625-3.262z");
}

.zowzdtb6j {
  fill: var(--svg-color--cabcf8, #cabcf8);
  d: path("m12 3l-5.625 9.166L12 9.651z");
}

</style>
