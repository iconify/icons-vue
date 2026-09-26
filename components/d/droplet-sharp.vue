<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6_qklbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-sharp" /></template>
<style>
.c6_qklbkh {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.2175 9.3333C18.3654 10.6167 19 12.2782 19 14C19 17.866 15.866 21 12 21C8.134 21 5 17.866 5 14C5 12.2782 5.6346 10.6167 6.7825 9.3333L12 3.5L17.2175 9.3333Z");
}

</style>
