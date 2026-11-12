<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir2w2magc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:head-heart-fill" /></template>
<style>
.ir2w2magc {
  fill: currentColor;
  d: path("M6 18.519C3.211 16.45 2.001 13.41 2 10c.001-4.551 3.449-7.999 8-8c2.136 0 4.189.775 5.707 2.293c1.428 1.428 2.211 3.357 2.287 5.365L20.8 13.4A.999.999 0 0 1 20 15h-2v3a1 1 0 0 1-1 1h-3v2a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Zm4-10.566a3.6 3.6 0 0 0-1.876-.82c-1.216-.152-2.375.369-2.872 1.531C5.072 9.085 5 9.544 5 10c.001 1.465 1.321 2.985 2.293 3.957A21 21 0 0 0 9.4 15.8a1 1 0 0 0 1.2 0q.34-.258.665-.532q.751-.622 1.442-1.311c.972-.972 2.292-2.492 2.293-3.957c0-.456-.072-.915-.252-1.336c-.497-1.162-1.656-1.683-2.872-1.531a3.6 3.6 0 0 0-1.876.82");
}

</style>
