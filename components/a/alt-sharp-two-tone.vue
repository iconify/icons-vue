<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jslpj0brj"/><path clip-rule="evenodd" class="xp4r-wu4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alt-sharp-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jslpj0brj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 2V4H16.65L8.914 21.406C8.754 21.767 8.395 22 8 22H2V20H7.35L15.115 2.529C15.296 2.242 15.654 2 16 2H22Z");
}

.xp4r-wu4z {
  fill-rule: evenodd;
  d: path("M22 20V22H12V20H22Z");
}

</style>
