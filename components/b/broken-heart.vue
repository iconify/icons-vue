<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<g class="sdcfnj7sm"><path class="ohba2e8ea"/><path class="d3_n7iboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:broken-heart" /></template>
<style>
.d3_n7iboh {
  d: path("M26.018 1.966c-2.765 0-5.248 1.151-7.037 2.983l-4.042 6.737l6.039 5.176a1.5 1.5 0 0 1 .274 1.966l-4.604 6.962l4.161 6.935c6.338-3.529 13.621-11.263 14.809-18.649c.17-.721.268-1.469.268-2.241c-.001-5.452-4.419-9.869-9.868-9.869");
}

.ohba2e8ea {
  d: path("M13.589 26.521a1.5 1.5 0 0 1 .035-1.599l4.395-6.646l-5.995-5.139a1.5 1.5 0 0 1-.31-1.911l4.304-7.172a9.78 9.78 0 0 0-6.035-2.09c-5.45 0-9.868 4.417-9.868 9.868c0 .772.098 1.52.266 2.241C1.751 22.587 11.216 31.568 18 34.034l.077-.032z");
}

.sdcfnj7sm {
  fill: var(--svg-color--dd2e44, #dd2e44);
}

</style>
