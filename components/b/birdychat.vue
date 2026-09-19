<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ojk3o0pzv"/><path class="t3lrklpmh"/><circle transform="rotate(-.166 13.945 17.811)" class="zki5ggh5n"/><path class="fuvs70arn"/><path class="k5s-43qvx"/><path class="yowx-0daw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:birdychat" /></template>
<style>
.fuvs70arn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.57 29.429c-3.085-.101-6.242-.65-8.922-1.564a51 51 0 0 1 4.814-3.542");
}

.k5s-43qvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.118 15.99c.883 3.983-.076 8.618-1.47 11.875");
}

.ojk3o0pzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.919 35.703C3.676 32.308 2.5 28.373 2.5 24C2.5 12.126 12.126 2.5 24 2.5c5.702 0 11.17 2.265 15.201 6.298c8.396 8.392 8.399 22.001.007 30.397l-.007.007A21.5 21.5 0 0 1 24 45.5a21.96 21.96 0 0 1-11.91-3.515c-1.714 1.41-3.546 2.279-5.461 2.713q-.794.18-1.614-.186q-.817-.364-.622-1.677q.383-2.574 1.335-5.03c.27-.696.42-1.308.192-2.102");
}

.t3lrklpmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.43 6.071q5.43 4.314 7.688 9.918q5.517.646 8.568 2.817q-.85 2.29-5.224 5.517q3.286 2.201 4.109 5.106q-2.436 2.817-7.101 2.112c-1.976 4.753-5.534 8.066-8.38 10.443");
}

.yowx-0daw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.47 31.541c-.854-.01-1.784-.086-2.327-.32q.217-1.28-.3-2.762c.267-.088.805-.594.805-.594");
}

.zki5ggh5n {
  cx: 13.946px;
  cy: 17.806px;
  r: 1.603px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
