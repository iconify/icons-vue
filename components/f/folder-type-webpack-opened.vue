<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGmIJLHh1T" cx="-100.943" cy="-69.047" r=".004" gradientTransform="matrix(2074.534 0 0 -2395.464 209432.559 -165379.819)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sabca2ywv"/><stop offset=".593" class="bow5c8bgj"/><stop offset="1" class="ezk-b-b1n"/></radialGradient></defs><path class="d5yxcfbux"/><path class="ov4ul_bbp"/><path fill="url(#SVGmIJLHh1T)" class="vl8691bkc"/><path class="k7314yi1f"/><path class="ox9bwy4-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-webpack-opened" /></template>
<style>
.bow5c8bgj {
  stop-color: var(--svg-color--b9d1f8, #b9d1f8);
}

.d5yxcfbux {
  fill: var(--svg-color--8da2cc, #8da2cc);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.ezk-b-b1n {
  stop-color: var(--svg-color--9cb6e0, #9cb6e0);
}

.k7314yi1f {
  fill: var(--svg-color--6f95db, #6f95db);
  d: path("m21.9 15.35l-4.5 2.6v5.2l4.5 2.6l4.5-2.6v-5.2Z");
}

.ov4ul_bbp {
  fill: var(--svg-color--8da2cc, #8da2cc);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.ox9bwy4-l {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-1, 0.1);
  d: path("m21.9 10l-9.1 5.278l9.1 4.954L31 15.31Zm0 10.911l-9.1 4.824l9.1 5.245l9.066-5.28z");
}

.sabca2ywv {
  stop-color: var(--svg-color--93b4e7, #93b4e7);
}

.vl8691bkc {
  d: path("m21.9 10.032l-9.079 5.242v10.484L21.9 31l9.079-5.242V15.274Z");
}

</style>
