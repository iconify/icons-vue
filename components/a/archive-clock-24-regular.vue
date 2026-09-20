<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b29d_bddw"/><path class="sqsqwcdlj"/><path class="kgkoscw3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-24-regular" /></template>
<style>
.b29d_bddw {
  d: path("M23 17.5a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0M17.5 14a.5.5 0 0 1 .5.5V17h2a.5.5 0 0 1 0 1h-2.5a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kgkoscw3l {
  d: path("M13.75 11a.75.75 0 0 1 .749.733a6.5 6.5 0 0 0-1.151.767H10.25a.75.75 0 0 1 0-1.5z");
}

.sqsqwcdlj {
  d: path("M18.75 3A2.25 2.25 0 0 1 21 5.25v1.5c0 .78-.397 1.467-1 1.871v2.877a6.5 6.5 0 0 0-1.5-.422V9h-13v8.25a2.25 2.25 0 0 0 2.25 2.25h3.565a6.4 6.4 0 0 0 .71 1.5H7.75A3.75 3.75 0 0 1 4 17.25V8.621A2.25 2.25 0 0 1 3 6.75v-1.5A2.25 2.25 0 0 1 5.25 3zM5.25 4.5a.75.75 0 0 0-.75.75v1.5c0 .414.336.75.75.75h13.5a.75.75 0 0 0 .75-.75v-1.5a.75.75 0 0 0-.75-.75z");
}

</style>
