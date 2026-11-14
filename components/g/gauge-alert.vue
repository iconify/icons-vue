<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gdi5anbck"/><path class="tfd2rkbmf"/><path class="ysmxbwq8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gauge-alert" /></template>
<style>
.gdi5anbck {
  d: path("M3 14q0-.221.011-.442q.011-.22.033-.44q.021-.22.054-.438q.032-.219.075-.435q.044-.217.097-.431q.054-.215.118-.426t.139-.419q.074-.208.159-.412t.179-.404t.199-.394q.104-.195.217-.385q.114-.189.237-.373q.123-.183.254-.361q.132-.177.272-.348t.289-.334q.148-.164.304-.32t.32-.304q.164-.149.335-.289q.17-.14.348-.272q.177-.131.361-.254q.184-.122.373-.236t.384-.218t.395-.198t.404-.179t.412-.159t.419-.139q.211-.064.426-.117q.214-.054.431-.097q.216-.043.435-.076q.218-.032.438-.054t.44-.032q.221-.011.442-.011q.217 0 .433.011t.432.031q.216.021.43.052t.427.072t.423.093t.418.114t.412.133q.205.072.406.153q.2.082.397.172q.197.091.389.192q.192.1.379.209q.187.11.368.228q.182.118.357.245q.176.127.345.262q.169.136.332.279t.318.294t.304.309t.288.323t.273.337q.132.171.256.349q.123.178.238.362q.115.183.222.372q.106.189.203.383q.096.193.184.392q.087.198.165.4t.146.408t.126.414t.106.42t.086.425t.065.428t.044.431t.024.432M3 14h2m7 0l4.626-3.331");
}

.tfd2rkbmf {
  fill: currentColor;
  d: path("M10.75 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysmxbwq8a {
  d: path("m18 14l4 7.5h-8Zm0 3.25v1M18 20h.01");
}

</style>
