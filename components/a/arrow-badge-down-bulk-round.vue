<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4of-9bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-down-bulk-round" /></template>
<style>
.o4of-9bxv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 6v6c0 1.039-.578 1.992-1.293 2.707l-5 5a2.414 2.414 0 0 1-3.414 0l-5-5C4.578 13.992 4 13.039 4 12V6c0-.898.572-1.928 1.521-2.089a1.34 1.34 0 0 1 1.186.382l5 5a.414.414 0 0 0 .586 0l5-5a1.36 1.36 0 0 1 1.186-.382C19.428 4.072 20 5.102 20 6");
}

</style>
