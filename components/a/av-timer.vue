<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmfmp3f9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:av-timer" /></template>
<style>
.wmfmp3f9i {
  fill: currentColor;
  d: path("M8.888 19.374q-1.455-.626-2.546-1.716t-1.716-2.55T4 12q0-.965.212-1.849q.211-.884.59-1.671q.379-.788.916-1.46q.538-.672 1.19-1.22l6.107 6.108l-.707.708l-5.4-5.4q-.789.88-1.349 2.05T5 12q0 2.9 2.05 4.95T12 19t4.95-2.05T19 12q0-2.617-1.76-4.651T12.5 5.023V7h-1V4h.5q1.649 0 3.108.626t2.55 1.716t1.716 2.55T20 12t-.626 3.108t-1.716 2.55t-2.546 1.716T12 20t-3.113-.626m-2.436-6.826q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221m5 5q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221m5-5q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221");
}

</style>
