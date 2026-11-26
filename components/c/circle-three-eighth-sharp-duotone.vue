<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g9eou3b7p"/><path class="uu4k43bji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-three-eighth-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g9eou3b7p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1Z");
}

.uu4k43bji {
  d: path("M12 12L12 5C15.866 5 19 8.134 19 12C19 13.8565 18.2625 15.637 16.9497 16.9497Z");
}

</style>
