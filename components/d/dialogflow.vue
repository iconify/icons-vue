<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":326};
const content = `<defs><path id="SVGsfyJ6bpP" class="bbjcp2b9x"/></defs><mask id="SVGnOQMPeSe" class="n1mjunbsu"><use href="#SVGsfyJ6bpP"/></mask><path mask="url(#SVGnOQMPeSe)" class="ql8acjxwz"/><path mask="url(#SVGnOQMPeSe)" class="lq9h0bfqf"/><path mask="url(#SVGnOQMPeSe)" class="db_t_rbsp"/><path mask="url(#SVGnOQMPeSe)" class="r0xme7quw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dialogflow" /></template>
<style>
.bbjcp2b9x {
  d: path("M244.828 64.429L139.051 3.389a22.13 22.13 0 0 0-22.188 0L11.067 64.428A22.26 22.26 0 0 0 0 83.666v122.171a22.19 22.19 0 0 0 11.067 19.184l52.925 30.592v62.372a6.658 6.658 0 0 0 9.987 5.74l170.957-98.65a22.13 22.13 0 0 0 11.068-19.184V83.648a22.31 22.31 0 0 0-11.176-19.219");
}

.db_t_rbsp {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M125.716 142.493L.81 70.386l-.81.485l127.984 73.872l127.912-73.872l-3.006-1.781z");
}

.lq9h0bfqf {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M127.984 144.743L0 70.871L127.984-3l127.912 73.871z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.ql8acjxwz {
  fill: var(--svg-color--ef6c00, #ef6c00);
  d: path("m255.896 70.871l-127.912 73.872L0 70.871v147.743l63.992 36.909v73.889l191.904-110.798z");
}

.r0xme7quw {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M127.984 145.661v-.918L.81 71.303l-.81.486z");
}

</style>
