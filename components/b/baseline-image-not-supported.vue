<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb92cxbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-image-not-supported" /></template>
<style>
.fb92cxbki {
  fill: currentColor;
  d: path("m21.9 21.9l-8.49-8.49l-9.82-9.82L2.1 2.1L.69 3.51L3 5.83V19c0 1.1.9 2 2 2h13.17l2.31 2.31zM5 18l3.5-4.5l2.5 3.01L12.17 15l3 3zm16 .17L5.83 3H19c1.1 0 2 .9 2 2z");
}

</style>
