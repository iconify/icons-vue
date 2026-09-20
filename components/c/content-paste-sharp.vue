<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjsgx4b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:content-paste-sharp" /></template>
<style>
.yjsgx4b8e {
  fill: currentColor;
  d: path("M3 21V3h6.175q.275-.875 1.075-1.437T12 1q1 0 1.788.563T14.85 3H21v18zm2-2h14V5h-2v3H7V5H5zm7.713-14.288Q13 4.425 13 4t-.288-.712T12 3t-.712.288T11 4t.288.713T12 5t.713-.288");
}

</style>
