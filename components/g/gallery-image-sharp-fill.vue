<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="q1hoe7v4j"/><path class="nqfya7b3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-image-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nqfya7b3m {
  d: path("M20 2V4H4V2H20Z");
}

.q1hoe7v4j {
  fill-rule: evenodd;
  d: path("M21 6C21.552 6 22 6.45 22 7V21C22 21.55 21.552 22 21 22H3C2.448 22 2 21.55 2 21V7C2 6.45 2.448 6 3 6H21ZM4 16.96V20H20V15.96L17.093 13.06L13.092 16.06L9 11.96L4 16.96ZM13.5 10C12.672 10 12 10.67 12 11.5C12 12.33 12.672 13 13.5 13C14.328 13 15 12.33 15 11.5C15 10.67 14.328 10 13.5 10Z");
}

</style>
