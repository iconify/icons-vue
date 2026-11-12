<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uzs4kbcpc"/><path class="sq-fozcsg"/><path clip-rule="evenodd" class="yo0ngqbsu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cbbtc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sq-fozcsg {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.516 11.01c.157-1.048-.642-1.611-1.732-1.987l.353-1.42l-.864-.215l-.344 1.382q-.344-.085-.693-.163l.348-1.391L11.72 7l-.354 1.42a25 25 0 0 1-.553-.13l.002-.005l-1.192-.298l-.23.924s.641.146.627.155c.35.088.414.32.403.503l-.403 1.618q.045.012.09.029l-.091-.023l-.566 2.266c-.042.106-.151.266-.396.205q-.316-.07-.628-.156L8 14.497l1.125.28l.616.159l-.358 1.436l.864.215l.354-1.42q.352.095.688.178l-.352 1.414l.864.215l.357-1.433c1.474.28 2.582.167 3.049-1.166c.375-1.073-.019-1.693-.795-2.096c.565-.13.99-.502 1.104-1.269m-1.975 2.769c-.267 1.073-2.074.493-2.66.348l.475-1.903c.586.146 2.464.436 2.185 1.555m.268-2.784c-.244.976-1.748.48-2.235.358l.43-1.725c.487.121 2.059.348 1.805 1.367");
}

.uzs4kbcpc {
  fill: var(--svg-color--0052ff, #0052ff);
  d: path("M24 0H0v24h24z");
}

.yo0ngqbsu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.25a7.25 7.25 0 1 0 0-14.499a7.25 7.25 0 0 0 0 14.499M20 12a8 8 0 1 1-16.001 0A8 8 0 0 1 20 12");
}

</style>
