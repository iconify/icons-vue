<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="a9dlxfb5f"/><path clip-rule="evenodd" class="amzsjib5i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctk-background" /></template>
<style>
.a9dlxfb5f {
  fill: var(--svg-color--e1ab4b, #e1ab4b);
  d: path("M24 0H0v24h24z");
}

.amzsjib5i {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.548 20H6.504c-.438 0-.8-.282-.833-.71L4.94 8.418a.8.8 0 0 1 .396-.744l6.268-3.548A.9.9 0 0 1 12.028 4c.156 0 .316.042.452.122l6.174 3.365a.8.8 0 0 1 .405.748l-.673 11.05c-.028.423-.395.715-.838.715m-.814-1.882h-9.42l-.66-8.989l5.384-3.247l5.303 3.092l-.611 9.144zm-8.17-8.23l.198 3.524h4.895l-.1 1.411h-2.936l-.075-.94h-1.76l.155 2.823h6.18L15.444 12h-5.036l-.094-1.13l1.709-1.223l1.858 1.224v.658h1.596l.113-1.642l-3.516-2.122z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
