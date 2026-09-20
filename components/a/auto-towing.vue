<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqtk0mvxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-towing" /></template>
<style>
.gqtk0mvxg {
  fill: currentColor;
  d: path("M1.616 16.385v-2H11.7L2.885 7.446v3.439h-1v-5h.384l12.116 6.704V5.385h3.538l4.462 5.346v5.654h-2.231q.327 1.096-.375 2.048t-1.894.952t-1.894-.952t-.375-2.048H8.654q.327 1.096-.375 2.048q-.702.951-1.894.951q-1.193 0-1.894-.951q-.702-.952-.375-2.049zm5.844 1.67q.425-.443.425-1.055t-.425-1.056t-1.075-.444t-1.075.444T4.885 17t.425 1.056t1.075.444t1.075-.444m11.5 0q.424-.445.424-1.056t-.425-1.056t-1.075-.444t-1.075.444T16.385 17t.425 1.056t1.075.444t1.075-.444m-3.575-7.325h5.708l-3.657-4.346h-2.05z");
}

</style>
