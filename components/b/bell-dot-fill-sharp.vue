<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1no6b3xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-dot-fill-sharp" /></template>
<style>
.k1no6b3xp {
  fill: currentColor;
  d: path("M21 15v2a1 1 0 0 1-1 1h-4a4 4 0 0 1-8 0H4a1 1 0 0 1-1-1v-2c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C4 13.057 4 13.026 4 13V9c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 11 2a1 1 0 0 1 .919 1.394a6.62 6.62 0 0 0 .576 6.276c1.439 2.156 3.928 2.688 6.364 2.34A1 1 0 0 1 20 13c0 .026 0 .057.014.079c.048.081.128.148.193.214c.496.496.793.975.793 1.707M14.315 4.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
