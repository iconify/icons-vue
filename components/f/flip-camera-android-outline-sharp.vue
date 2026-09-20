<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuwyjwrhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flip-camera-android-outline-sharp" /></template>
<style>
.xuwyjwrhd {
  fill: currentColor;
  d: path("M12 21.5q-3.229 0-5.777-1.942T2.853 14.5h1.013q.815 2.708 3.061 4.354T12 20.5q2.516 0 4.577-1.399t3.285-3.601H16.5v-1h5v5h-1v-3.154q-1.367 2.304-3.592 3.729T12 21.5m-1.423-8.077Q10 12.846 10 12t.577-1.423T12 10t1.423.577T14 12t-.577 1.423T12 14t-1.423-.577M2.5 9.5v-5h1v3.154Q4.867 5.35 7.092 3.925T12 2.5q3.229 0 5.777 1.942q2.548 1.943 3.37 5.058h-1.012q-.816-2.708-3.062-4.354T12 3.5q-2.516 0-4.577 1.399T4.138 8.5H7.5v1z");
}

</style>
