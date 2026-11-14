<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq0ohc4ua"/><path class="p-bfwnbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-tag-protected" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oq0ohc4ua {
  d: path("M12.019 16H9.217q-.286 0-.565-.062q-.279-.061-.539-.182q-.259-.12-.487-.293q-.227-.174-.412-.392l-3.279-3.875q-.075-.088-.141-.182q-.067-.094-.124-.194q-.058-.1-.108-.204q-.049-.105-.088-.213q-.04-.108-.07-.219q-.03-.112-.05-.225q-.02-.114-.03-.229t-.01-.23t.01-.23t.03-.229q.02-.113.05-.225q.03-.111.07-.219q.039-.108.088-.213q.05-.104.108-.204t.124-.194t.141-.182l3.279-3.875q.185-.218.412-.392q.228-.173.487-.293q.26-.121.539-.182Q8.931 3 9.217 3h8.158q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v4.724M8 9.5h.01m8.178 7h3.625A2.19 2.19 0 0 1 22 18.688v1.125A2.19 2.19 0 0 1 19.813 22h-3.625A2.19 2.19 0 0 1 14 19.813v-1.125a2.19 2.19 0 0 1 2.188-2.188");
}

.p-bfwnbwt {
  d: path("M15.75 16.5V15a2.25 2.25 0 0 1 4.5 0v1.5");
}

</style>
