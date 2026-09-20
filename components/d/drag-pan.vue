<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-hjg7fxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drag-pan" /></template>
<style>
.p-hjg7fxd {
  fill: currentColor;
  d: path("M12 21.308L8.442 17.75l.714-.713L11.5 19.38V12.5H4.625l2.344 2.339l-.719.719L2.692 12l3.552-3.552l.714.714L4.619 11.5H11.5V4.62L9.156 6.963l-.714-.714L12 2.692l3.558 3.558l-.714.714L12.5 4.618V11.5h6.875l-2.344-2.339l.719-.719L21.308 12l-3.558 3.558l-.713-.714L19.38 12.5H12.5v6.875l2.339-2.344l.719.719z");
}

</style>
