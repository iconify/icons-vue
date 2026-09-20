<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo78eeb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:asterisk-outline" /></template>
<style>
.yo78eeb6o {
  fill: currentColor;
  d: path("M11 21v-6.6l-4.65 4.675l-1.425-1.425L9.6 13H3v-2h6.6L4.925 6.35L6.35 4.925L11 9.6V3h2v6.6l4.65-4.675l1.425 1.425L14.4 11H21v2h-6.6l4.675 4.65l-1.425 1.425L13 14.4V21z");
}

</style>
