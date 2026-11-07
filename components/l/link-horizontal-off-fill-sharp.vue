<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt28h-kum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-off-fill-sharp" /></template>
<style>
.gt28h-kum {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L11.586 13H8a1 1 0 0 1 0-2h1.586l-2-2H7a3 3 0 1 0 0 6h2a1 1 0 0 1 0 2H7a5 5 0 0 1-1.256-9.842L1.293 2.707a.999.999 0 1 1 1.414-1.414M17 7c1.33 0 2.597.522 3.536 1.464A4.98 4.98 0 0 1 22 12a4.97 4.97 0 0 1-.895 2.856a1 1 0 1 1-1.641-1.144A3.001 3.001 0 0 0 17 9h-2a1 1 0 0 1 0-2Z");
}

</style>
