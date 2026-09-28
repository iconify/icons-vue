<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":228};
const content = `<path class="v2hzhg-0u"/><path class="txh6r7joc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dify" /></template>
<style>
.txh6r7joc {
  fill: var(--svg-color--010916, #010916);
  d: path("M60.445.026H0v184.872h60.445c74.665 0 95.994-42.657 95.994-92.449S135.109.026 60.445.026m.719 156.434H34.137V28.464h27.027c42.94 0 61.164 21.071 61.164 63.985s-18.224 63.986-61.164 63.986zm417.058-99.558l-28.438 92.449l-28.44-92.45h-33.776l41.247 119.579c4.285 12.448-2.979 22.637-16.145 22.637h-14.45v28.439h21.251c18.532 0 35.215-11.73 41.477-29.157L512 56.902z");
}

.v2hzhg-0u {
  fill: var(--svg-color--03f, #03f);
  d: path("M339.852.026h36.987v28.438H327.07v28.438h49.769V85.34H327.07v71.12h49.769v28.438H163.522V156.46h46.945V85.34h-39.81V56.902h71.098v99.584h54.054v-71.12h-32.7v-28.44h32.7V44.12h-.053c0-24.306 19.79-44.094 44.096-44.094M226.124 0c14.552 0 19.916 8.906 19.916 19.917c0 11.01-5.389 19.917-19.916 19.917c-14.553 0-19.917-8.906-19.917-19.917C206.207 8.907 211.57 0 226.124 0");
}

</style>
