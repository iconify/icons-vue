<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q-_d_htgx"/><path class="h8vu7_tub"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dmd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h8vu7_tub {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.871 13.434a8 8 0 0 0-.011-2.93L17 9.997v3.99zm-.142.638l-2.613.502v.005l1.02 2.555a8 8 0 0 0 1.593-3.062m-2.048 3.56l-.023.022l-2.744-1.097l1.674-1.674zm-.512.473a8 8 0 0 1-3.015 1.6l.461-2.625zm-3.652 1.75L14.025 17H10.04l.556 2.876a8 8 0 0 0 2.92-.02m-3.558-.119l-.509-2.65l-2.6 1.035a8 8 0 0 0 3.11 1.616zm-4.054-2.555l1.038-2.598l-2.66-.466a8 8 0 0 0 1.622 3.064m-1.768-3.7a8 8 0 0 1-.009-2.913L7 10.008v3.986zm.133-3.55l2.669-.513l-1.032-2.602A8 8 0 0 0 4.27 9.931m2.09-3.603L9.136 7.44l-1.67 1.674zm.492-.45a8 8 0 0 1 3.052-1.6L9.44 6.912zm3.684-1.744l-.505 2.892h3.99l-.558-2.892a8 8 0 0 0-2.927 0m3.564.145l.506 2.628l2.561-1.015A8 8 0 0 0 14.1 4.28m3.554 2.06l.03.032l-1.094 2.743l-1.675-1.674zm.477.52a8 8 0 0 1 1.582 3.007l-2.605-.457zm-6.102 4.471l1.868-3.83h-3.733zM7.5 10.132v3.733l3.861-1.869zm8.694-.571l-1.732-1.726l-1.76 3.486zm.306 4.304v-3.733l-3.812 1.864zm-7.355 2.697l-.003-.004l.004-.001zm-.003-.004l-2.784 1.107l1.113-2.777zm7.052-2.122l-.003-.002l.003-.003zm-3.486-1.76l3.483 1.758l-1.724 1.728zm-.68-.019L10.163 16.5h3.733zM7.866 9.561l3.486 1.76l-1.76-3.486zm0 4.87l.003.003l-.003.002zm.003.003l1.724 1.728l1.76-3.486z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-_d_htgx {
  fill: var(--svg-color--0245b2, #0245b2);
  d: path("M24 0H0v24h24z");
}

</style>
