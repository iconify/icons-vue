<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcj-f4euf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-profile" /></template>
<style>
.vcj-f4euf {
  fill: currentColor;
  d: path("M8.692 21q-.348 0-.578-.23t-.23-.578V5.288q0-.348.23-.578t.578-.23h1.616V3h3.384v1.48h1.616q.348 0 .578.23t.23.579v5.577q-2.472.153-4.166 1.957t-1.694 4.306q0 1.06.354 2.052q.356.992 1.015 1.819zm7.366 0l-.108-.865q-.57-.125-.937-.352q-.369-.227-.696-.562l-.796.366l-.577-.86l.702-.577q-.184-.548-.184-1.032t.184-1.031l-.702-.577l.577-.86l.796.366q.327-.335.696-.565t.937-.355l.108-.865h1l.108.865q.569.125.937.352t.695.562l.796-.366l.577.86l-.702.577q.185.548.185 1.032t-.185 1.031l.702.577l-.577.86l-.796-.36q-.327.335-.695.562q-.369.226-.937.351l-.108.866zm.5-1.73q.882 0 1.518-.636t.636-1.519t-.636-1.518t-1.518-.636t-1.519.636t-.635 1.518t.635 1.519t1.519.635");
}

</style>
