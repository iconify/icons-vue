<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x2jqgqy5p"/><path class="l5o7hcc3t"/><path class="drt80sbho"/><path class="n4q1418kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-jamaica" /></template>
<style>
.drt80sbho {
  fill: var(--svg-color--128807, #128807);
  d: path("M4.144 52.27C5.678 53.359 7.626 54 10 54h44c2.344 0 4.271-.625 5.796-1.69L31.935 36.262z");
}

.l5o7hcc3t {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M63.772 45.588c.146-.831.228-1.695.228-2.588V21a14.7 14.7 0 0 0-.31-3.03L39.756 31.754l24.02 13.831M.297 18.04A14.8 14.8 0 0 0 0 21v22c0 .869.077 1.71.215 2.521l23.898-13.765z");
}

.n4q1418kp {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("m63.772 45.588l-24.02-13.831l23.934-13.784c-.585-2.799-2.02-5.139-4.284-6.544L31.931 27.251L4.529 11.469C2.281 12.89.864 15.237.293 18.04l23.816 13.717L.211 45.521c.48 2.826 1.794 5.229 3.929 6.748l27.791-16.01l27.861 16.05c2.152-1.503 3.483-3.898 3.976-6.722");
}

.x2jqgqy5p {
  fill: var(--svg-color--128807, #128807);
  d: path("M59.41 11.429C57.95 10.523 56.15 10 54.004 10h-44c-2.178 0-3.996.54-5.467 1.469l27.401 15.782z");
}

</style>
