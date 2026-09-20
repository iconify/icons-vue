<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s7h04rdua"/><path class="qxwxnhbhy"/><path class="yfo1v5ftn"/><path class="l91vssbqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exact-search-outline-bold" /></template>
<style>
.l91vssbqw {
  d: path("M15 21h6");
}

.qxwxnhbhy {
  d: path("M12.5 12.5 16 16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s7h04rdua {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
}

.yfo1v5ftn {
  d: path("M15 17.5h6");
}

</style>
