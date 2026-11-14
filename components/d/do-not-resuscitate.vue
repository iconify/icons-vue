<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wda1q9hvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:do-not-resuscitate" /></template>
<style>
.wda1q9hvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.402 16.859A41 41 0 0 1 11 18.5a45 45 0 0 1-1.513-1.004m-4.245-3.683C3.721 12.009 3 10.149 3 8c0-2.5 2-4.5 4.25-4.5c1.75 0 3 1 3.75 2.25c.75-1.25 2-2.25 3.75-2.25q.348 0 .686.062M19 7.986V8c0 1.808-.511 3.412-1.579 4.95M19.5 3.5l-16 16m14.407-3.657l-1.685 1.685a.57.57 0 0 0 .403.972a1.016 1.016 0 0 1 .971 1.314l-.096.311a.422.422 0 0 0 .702.423l1.826-1.826a.57.57 0 0 0-.403-.972a1.074 1.074 0 0 1-1.042-1.334l.042-.166a.428.428 0 0 0-.718-.407");
}

</style>
