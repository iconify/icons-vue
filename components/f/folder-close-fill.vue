<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0t0owbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-close-fill" /></template>
<style>
.o0t0owbdd {
  fill: currentColor;
  d: path("M12.414 5H19a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293ZM12 11.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414L10.586 13l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 14.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 13l1.293-1.293a.999.999 0 1 0-1.414-1.414Z");
}

</style>
