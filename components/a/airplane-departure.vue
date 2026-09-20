<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v90eji9nv"/><circle class="vhkgl9l-a"/><circle class="qiccdy7aa"/><path class="gwh0f6bfh"/><path class="hl4x4oxnw"/><path class="xu79hb9bf"/><path class="pu39ocbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:airplane-departure" /></template>
<style>
.gwh0f6bfh {
  fill: var(--svg-color--0f6da0, #0f6da0);
  d: path("M113.4 24.4s.2 4.1-7 6.2c-1.1.4.2 4.3 1.2 4.3c1.2 0 14.8-4.7 14.6-9.4c-3-1.3-8.8-1.1-8.8-1.1");
}

.hl4x4oxnw {
  fill: var(--svg-color--757f3f, #757f3f);
  d: path("M128 117.2c0 1.5-1.2 2.7-2.7 2.7H2.6c-1.5 0-2.7-1.2-2.7-2.7s1.2-2.7 2.7-2.7h122.7c1.5 0 2.7 1.2 2.7 2.7");
}

.pu39ocbsr {
  fill: var(--svg-color--0f6da0, #0f6da0);
  d: path("M87 49.4c.3-.3.4-.8.2-1.2c-.7-1.3-2.8-4-7.7-4c-5.1 0-18.2 7.8-24 11.1c-.9.5-.9 1.7 0 2.3c1.3.7 1.7 2.4 1 3.7L44.1 82.9c-.7 1.3.3 2.9 1.8 2.9h1.3c2.8 0 5.5-1.2 7.4-3.2zM24.6 62.6c-2.3 1.2-5.1 2.6-6.5 3.4c-.3.2-.6.5-.8.9l-1.8 6.7c-.4 1.8 1.9 2.9 3.1 1.5l8.4-11c.9-1.3-.4-2.6-2.4-1.5m4.1-7.7c-.3-1.4-6.5-.9-11.5-3.1c-6.6-2.9-10.3-4.9-13.5-6.4c-1.7-.8-3.3.8-2.1 2.5l11 15.7c.3.4.9.5 1.3.3c0 0 9.9-5.2 14.8-9m92.2-33.1s-1.9 2.7-6.5 5.1c-1.1.6-2.5.1-3-1c-.4-1-.1-2.1.8-2.7c.7-.5 1.6-1.1 2.2-1.5c1.4-1.2 2.6-2.6 2.6-2.6s1.6 1 3.9 2.7");
}

.qiccdy7aa {
  cx: 110.6px;
  cy: 42px;
  r: 3.5px;
  fill: var(--svg-color--78a3ad, #78a3ad);
}

.v90eji9nv {
  fill: var(--svg-color--0f6da0, #0f6da0);
  d: path("m84.7 42.3l-40.3-5.5c-1.4-.2-2.9-.1-4.3.2c-2.2.5-2.6 3.5-.6 4.6l19.9 10.1z");
}

.vhkgl9l-a {
  cx: 73.4px;
  cy: 64.8px;
  r: 3.5px;
  fill: var(--svg-color--78a3ad, #78a3ad);
}

.xu79hb9bf {
  fill: var(--svg-color--48c0e5, #48c0e5);
  d: path("M12.9 64c-.8-.7-.6-2.1.4-2.6c13-6.1 84-39.1 91.1-42.5c7.8-3.7 13.6.7 15.6 2.4s4.3.5 5.7 2.6c1.4 2 1 7.6-14.7 14.8c-16.9 7.8-51.8 23.8-58.9 26.8c-6.8 2.9-27.8 8.2-39.2-1.5");
}

</style>
