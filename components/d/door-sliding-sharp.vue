<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khm3-7bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-sliding-sharp" /></template>
<style>
.khm3-7bru {
  fill: currentColor;
  d: path("M9.713 12.713Q10 12.425 10 12t-.288-.712T9 11t-.712.288T8 12t.288.713T9 13t.713-.288m6 0Q16 12.426 16 12t-.288-.712T15 11t-.712.288T14 12t.288.713T15 13t.713-.288M3 21v-2h1V3h7.5v16h1V3H20v16h1v2z");
}

</style>
