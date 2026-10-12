<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cmt7sk8xp"/><path class="tdbazkbev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guest-book" /></template>
<style>
.cmt7sk8xp {
  d: path("m15.53 6.22l.34-.94q.13-.38.48-.57l3.4-1.87q.35-.19.58.14l.54.79q.23.33-.12.53l-3.3 1.9q-.35.2-.75.25l-.9.1q-.4.05-.27-.33M12 10.75c-2.25-1.5-5.75-2-9.25-1.25v10.75c3.25-.75 6.5-.25 9.25 1c2.75-1.25 6-1.75 9.25-1V9.5c-3.5-.75-7-.25-9.25 1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tdbazkbev {
  d: path("M12 10.75v10.5M4.5 13c1.75-.25 3.5 0 5 .75m-5 2.5c1.75-.25 3.5 0 5 .75m5-.75c.75-1.5 1.5-1.5 1.5 0s.75 1.5 1.5 0s1-1.25 1.75-.25");
}

</style>
