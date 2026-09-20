<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="whdr9-_hm"/><path class="qk0ytxb-y"/><path class="uyi75lb5m"/><circle class="a_5uuq8-m"/><circle class="e5pxnfxkv"/><path class="zcd6mle0u"/><path class="mc-c1l6ee"/><path class="dwil2zbnz"/><path class="ya9s2sbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:altos-odyssey" /></template>
<style>
.a_5uuq8-m {
  cx: 19.222px;
  cy: 13.888px;
  r: 0.75px;
  fill: currentColor;
}

.dwil2zbnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.673 39.17l7.419.701a4.335 4.335 0 1 0 .814-8.631l-9.66-.908m-16.267-2.814l-1.128-.055a4.468 4.468 0 0 0-.645 8.91l.211.021m14.14-25.072c1.34-1.072 1.973-3.922 1.242-5.359M16.79 37.582c3.528.317 8.94.365 12.604 0");
}

.e5pxnfxkv {
  cx: 23.266px;
  cy: 13.888px;
  r: 0.75px;
  fill: currentColor;
}

.mc-c1l6ee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.761 42.185c.147-5.26-.206-14.006-.206-14.006M27.61 23.56c.09 5.131 1.965 14.997 2.623 18.749M27.926 21.93c2.136 3.594 2.295 8.613 2.295 8.613");
}

.qk0ytxb-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.42 18.484c1.948.812 2.484 2.783 4.53 2.783s3.768-2.068 3.865-3.822c1 .08 1.446-1.933 0-2.03c.065-.942.69-3.63-1.258-4.093c-.926 1.267-5.521.976-6.958.367");
}

.uyi75lb5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.22 17.299c.837.17 2.396-.106 2.973-.447");
}

.whdr9-_hm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.73 5.5c4.578 0 5.05 1.81 5.148 5.091c.097 3.28.585 8.023 0 11.66c-.585 3.639-2.209 6.075-4.45 6.075s-3.703-6.253-7.178-6.253c-.563 0-1.16.221-1.767.592c.987-2.232 2.936-4.18 2.936-4.18c-.097-2.73-1.012-12.985 5.31-12.985");
}

.ya9s2sbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.316 42.185c-.025-1.776-.512-4.347-.512-4.347m11.421 1.668c.979 1.78.395 3.963-3.04 2.53m-9.677-26.64c.07.189.475.21.587.098");
}

.zcd6mle0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.483 22.665c-1.96 3.2-4.007 5.563-4.348 19.52m7.285-15.808c-1.682 3.118-2.437 5.866-2.486 15.807");
}

</style>
