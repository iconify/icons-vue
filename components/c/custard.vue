<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tb7l8nb-z"/><path class="maxa9ob7c"/><path class="rpexu8b-o"/><ellipse class="zxqmdd0_p"/><path class="fu62x5jov"/><path class="tnfhp9b8n"/><path class="q7yqq__ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:custard" /></template>
<style>
.fu62x5jov {
  fill: var(--svg-color--ffd170, #ffd170);
  d: path("M45.6 16.8H18.4s-3.1 17.3-3.1 17.5c0 3.8 7.5 6.8 16.7 6.8s16.7-3 16.7-6.8c0-.2-3.1-17.5-3.1-17.5");
}

.maxa9ob7c {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M60.5 34.8C60.5 43.2 47.7 50 32 50S3.5 43.2 3.5 34.8S16.3 19.6 32 19.6s28.5 6.8 28.5 15.2");
}

.q7yqq__ko {
  fill: var(--svg-color--a8521a, #a8521a);
  d: path("M44.8 17.1c0-2.8-5.8-5.1-12.9-5.1S19 14.3 19 17.1s5.8 5.1 12.9 5.1c7.9-.1 12.9-3.6 12.9-5.1");
}

.rpexu8b-o {
  fill: var(--svg-color--a8521a, #a8521a);
  d: path("M51.5 25.8c-3.6-2-35.2-8.2-42.2 4.5c-1.9 3.5-.4 8.4 5.5 11.7c3.6 2.1 11.3 5.5 16.1 6.3c4.9.8 9.4-2.1 13.2-2.9c6.2-1.4 10.2-4.3 10.6-8.8c.4-4.6 2.6-7.5-3.2-10.8");
}

.tb7l8nb-z {
  fill: var(--svg-color--e0e1e5, #e0e1e5);
  d: path("M32 52C15.5 52 2 44.6 2 35.4c0-9.1 13.5-16.6 30-16.6s30 7.4 30 16.6S48.5 52 32 52");
}

.tnfhp9b8n {
  fill: var(--svg-color--7d3d15, #7d3d15);
  d: path("M45.9 17.9c0-3.1-6.2-5.7-13.9-5.7s-13.9 2.5-13.9 5.7s6.2 5.7 13.9 5.7c8.5 0 13.9-4 13.9-5.7");
}

.zxqmdd0_p {
  cx: 32px;
  cy: 33.7px;
  fill: var(--svg-color--7d3d15, #7d3d15);
  rx: 19.2px;
  ry: 10.7px;
}

</style>
