<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hegi67_8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:av-timer-outline-rounded" /></template>
<style>
.hegi67_8j {
  fill: currentColor;
  d: path("M8.888 19.374q-1.455-.626-2.546-1.716t-1.716-2.55T4 12q0-1.7.625-3.14t1.692-2.51q.237-.24.572-.236q.336.002.572.239l5.2 5.2q.141.14.15.344t-.15.364t-.353.16t-.354-.16L6.908 7.216q-.789.88-1.349 2.05T5 12q0 2.9 2.05 4.95T12 19t4.95-2.05T19 12q0-2.617-1.76-4.651T12.5 5.023V6.5q0 .213-.144.356T11.999 7t-.356-.144T11.5 6.5v-2q0-.213.144-.356T12 4q1.649 0 3.108.626t2.55 1.716t1.716 2.55T20 12t-.626 3.108t-1.716 2.55t-2.546 1.716T12 20t-3.113-.626m-2.436-6.826q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221m5 5q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221m5-5q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221");
}

</style>
