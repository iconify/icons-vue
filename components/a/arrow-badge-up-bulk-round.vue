<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2tcphbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-up-bulk-round" /></template>
<style>
.c2tcphbhk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 12v6c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-5-5a.414.414 0 0 0-.586 0l-5 5a1.36 1.36 0 0 1-1.186.382C4.572 19.928 4 18.898 4 18v-6c0-1.039.578-1.992 1.293-2.707l5-5a2.414 2.414 0 0 1 3.414 0l5 5C19.422 10.008 20 10.961 20 12");
}

</style>
