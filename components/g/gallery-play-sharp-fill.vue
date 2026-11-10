<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kpmt47bea"/><path class="nqfya7b3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-play-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kpmt47bea {
  fill-rule: evenodd;
  d: path("M21 6C21.552 6 22 6.45 22 7V21C22 21.55 21.552 22 21 22H3C2.448 22 2 21.55 2 21V7C2 6.45 2.448 6 3 6H21ZM10.062 9.56C9.757 9.35 9.305 9.35 8.978 9.53C8.798 9.66 8.557 10.04 8.5 10.26V17.74C8.57 18.01 8.782 18.37 9.032 18.5C9.359 18.67 9.757 18.65 10.062 18.44L15.376 14.83C15.613 14.66 15.792 14.23 15.828 13.95C15.771 13.71 15.584 13.31 15.376 13.17L10.062 9.56Z");
}

.nqfya7b3m {
  d: path("M20 2V4H4V2H20Z");
}

</style>
