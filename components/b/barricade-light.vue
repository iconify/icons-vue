<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hs_52rgln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:barricade-light" /></template>
<style>
.hs_52rgln {
  fill: currentColor;
  d: path("M224 66H32a14 14 0 0 0-14 14v72a14 14 0 0 0 14 14h26v34a6 6 0 0 0 12 0v-34h116v34a6 6 0 0 0 12 0v-34h26a14 14 0 0 0 14-14V80a14 14 0 0 0-14-14m2 14v53.52L170.48 78H224a2 2 0 0 1 2 2M32 78h49.52l76 76h-55L30 81.52V80a2 2 0 0 1 2-2m-2 74V98.48L85.52 154H32a2 2 0 0 1-2-2m194 2h-49.52l-76-76h55L226 150.48V152a2 2 0 0 1-2 2");
}

</style>
