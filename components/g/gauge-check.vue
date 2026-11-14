<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kbswp9l2b"/><path class="tfd2rkbmf"/><path class="s7v73ac1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gauge-check" /></template>
<style>
.kbswp9l2b {
  d: path("M3 14q0-.221.011-.442q.011-.22.033-.44q.021-.22.054-.438q.032-.219.075-.435q.044-.217.097-.431q.054-.215.118-.426t.139-.419q.074-.208.159-.412t.179-.404t.199-.394q.104-.195.217-.385q.114-.189.237-.373q.123-.183.254-.361q.132-.177.272-.348t.289-.334q.148-.164.304-.32t.32-.304q.164-.149.335-.289q.17-.14.348-.272q.177-.131.361-.254q.184-.122.373-.236t.384-.218t.395-.198t.404-.179t.412-.159t.419-.139q.211-.064.426-.117q.214-.054.431-.097q.216-.043.435-.076q.218-.032.438-.054t.44-.032q.221-.011.442-.011q.19 0 .381.008q.19.008.38.024q.189.016.378.04q.189.025.377.057q.187.032.373.072q.187.04.371.087q.184.048.366.104t.362.119t.356.134t.351.148q.173.079.344.164t.336.178q.166.093.329.192q.162.1.32.206t.311.219q.154.113.302.232q.149.119.292.245q.143.125.281.257q.138.131.27.268t.258.28t.246.29q.121.148.234.301q.114.152.221.31q.107.157.208.319q.1.161.194.327q.093.166.179.336q.087.17.166.343t.151.349t.136.356t.121.361t.105.366t.09.37M3 14h2m7 0V7.5");
}

.s7v73ac1b {
  d: path("m14.5 18l2.5 2.5l4.5-5");
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

</style>
