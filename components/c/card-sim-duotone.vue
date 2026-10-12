<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wwh1mrq4e"/><path class="vowaxx-sy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:card-sim-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vowaxx-sy {
  d: path("M8 13C8 11.8954 8.8954 11 10 11L14 11C15.1046 11 16 11.8954 16 13L16 17C16 18.1046 15.1046 19 14 19L10 19C8.8954 19 8 18.1046 8 17L8 13Z");
}

.wwh1mrq4e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4C4 2.3431 5.3431 1 7 1L13.1716 1C13.9672 1 14.7303 1.3161 15.2929 1.8787L19.1213 5.7071C19.6839 6.2697 20 7.0328 20 7.8284L20 20C20 21.6569 18.6569 23 17 23L7 23C5.3431 23 4 21.6569 4 20L4 4Z");
}

</style>
