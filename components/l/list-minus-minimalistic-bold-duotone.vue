<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="lbue7y00m"/><path class="twoigx9_z"/><path class="rg7rardxv"/></g><path class="b6-nrrb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-minus-minimalistic-bold-duotone" /></template>
<style>
.b6-nrrb9w {
  fill: currentColor;
  d: path("M21 17.25C21.4142 17.25 21.75 17.5858 21.75 18C21.75 18.4142 21.4142 18.75 21 18.75H14C13.5858 18.75 13.25 18.4142 13.25 18C13.25 17.5858 13.5858 17.25 14 17.25H21Z");
}

.lbue7y00m {
  d: path("M11 15.25C11.4142 15.25 11.75 15.5858 11.75 16C11.75 16.4142 11.4142 16.75 11 16.75H3C2.58579 16.75 2.25 16.4142 2.25 16C2.25 15.5858 2.58579 15.25 3 15.25H11Z");
}

.rg7rardxv {
  d: path("M21 5.25C21.4142 5.25 21.75 5.58579 21.75 6C21.75 6.41421 21.4142 6.75 21 6.75H3C2.58578 6.75 2.25 6.41421 2.25 6C2.25 5.58579 2.58578 5.25 3 5.25H21Z");
}

.twoigx9_z {
  d: path("M21 10.25C21.4142 10.25 21.75 10.5858 21.75 11C21.75 11.4142 21.4142 11.75 21 11.75H3C2.58579 11.75 2.25 11.4142 2.25 11C2.25 10.5858 2.58579 10.25 3 10.25H21Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
