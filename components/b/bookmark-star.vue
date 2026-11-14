<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l129t5tri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bookmark-star" /></template>
<style>
.l129t5tri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.375 2.25h-6.75q-1.398 0-2.386.989q-.989.988-.989 2.386V17.25q0 1.622 1.451 2.348t2.749-.248l1.425-1.069q1.125-.844 2.25 0l1.425 1.069q1.298.973 2.749.248q1.451-.726 1.451-2.348V5.625q0-1.398-.989-2.386q-.988-.989-2.386-.989M13.2 6.865l.162.368q.177.399.611.443l.401.041q.851.088 1.114.901q.264.812-.373 1.382l-.298.267q-.327.292-.235.719l.085.392q.182.836-.511 1.339q-.692.504-1.431.073l-.347-.202q-.378-.22-.755 0l-.348.202q-.739.431-1.431-.073q-.693-.503-.511-1.339l.085-.392q.092-.427-.234-.718l-.3-.269q-.636-.569-.372-1.381q.263-.813 1.113-.901l.401-.041q.435-.044.612-.444l.162-.367q.346-.783 1.2-.783t1.2.782z");
}

</style>
