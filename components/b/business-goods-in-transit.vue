<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aumrl2uwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:business-goods-in-transit" /></template>
<style>
.aumrl2uwu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.288 2.558l3 1.25q.103.042.189.113q.085.071.147.163t.094.199q.032.106.032.217v2.25q0 2.512-2.971 3.968l3.251 3.252q.106.105.163.243t.057.287v3q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.627q.127.436.127 1q0 2.5-2.5 2.5t-2.5-2.5q0-.564.127-1H14q-.105 0-.205-.029q-.101-.028-.19-.083t-.159-.133t-.117-.171q-.769.416-1.954.416H9.3q.2.458.2 1q.001 1.036-.732 1.768q-.732.733-1.768.733t-1.768-.733Q4.5 20.286 4.5 19.25q0-.55.206-1.014q-2.956-.202-2.956-3.361v-4.25q0-3.375 3.375-3.375h6.25q3.182 0 3.364 3h1.646q-2.135-1.37-2.135-3.5V4.5q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l3-1.25Q17.85 2.5 18 2.5t.288.058M20.75 16.75v-1.939l-3.061-3.061H14.75v3.125q0 1.125-.375 1.875z");
}

</style>
