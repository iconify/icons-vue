<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocm6awrgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:litter-scoop" /></template>
<style>
.ocm6awrgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.515L20.485 12l-5.657 5.657l-8.485-8.485Zm-1.414 9.899l-5.657 5.657m7.248-11.49l-1.768 1.767m3.889.354L12.53 11.47m3.889.353l-1.767 1.768");
}

</style>
