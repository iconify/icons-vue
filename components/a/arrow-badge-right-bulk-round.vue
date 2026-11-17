<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9uc0gb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-right-bulk-round" /></template>
<style>
.g9uc0gb_p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 20H6c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l5-5a.414.414 0 0 0 0-.586l-5-5a1.36 1.36 0 0 1-.382-1.186C4.072 4.572 5.102 4 6 4h6c1.039 0 1.992.578 2.707 1.293l5 5a2.414 2.414 0 0 1 0 3.414l-5 5C13.992 19.422 13.039 20 12 20");
}

</style>
