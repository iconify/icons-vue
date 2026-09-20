<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qcl4ii9bj"/><path class="ac2upwbci"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bts-background" /></template>
<style>
.ac2upwbci {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.425 14.218l-3.398-3.48v4.073h3.204q.047-.319.194-.593m1.359-.935a1.8 1.8 0 0 0-.93.407L7.028 9.776V4l4.757 4.223zm1.378.406a1.8 1.8 0 0 0-.946-.407v-3.013c1.095.076 2.255.517 3.066 1.249zm.624 1.122a1.8 1.8 0 0 0-.197-.599l2.165-2.21c.722.847 1.15 1.703 1.219 2.809zm-.25 1.199a1.8 1.8 0 0 0 .258-.75h3.179a5.14 5.14 0 0 1-1.219 3.015zm-1.32.838c.316-.036.616-.156.87-.346l2.196 2.25c-.811.731-1.971 1.171-3.066 1.248zm-1.285-.347c.25.187.543.306.853.345V20c-1.098-.075-2.245-.515-3.058-1.249zm-.707-1.242c.03.271.118.524.255.745l-2.217 2.262a5.14 5.14 0 0 1-1.235-2.999l.009-.008z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qcl4ii9bj {
  fill: var(--svg-color--35baeb, #35baeb);
  d: path("M24 0H0v24h24z");
}

</style>
