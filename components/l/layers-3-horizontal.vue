<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwer9_bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-3-horizontal" /></template>
<style>
.nwer9_bzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 18.761L12.918 21.438C12.545 22.187 11.455 22.187 11.082 21.438L9.75 18.761L6.603 12.438C6.466 12.162 6.466 11.838 6.603 11.562L9.75 5.239L11.082 2.562C11.455 1.813 12.545 1.813 12.918 2.562L14.25 5.239M14.25 18.761L12 14.24L11.103 12.438C10.966 12.162 10.966 11.838 11.103 11.562L12 9.76L14.25 5.239L15.582 2.562C15.955 1.813 17.045 1.813 17.418 2.562L21.897 11.562C22.034 11.838 22.034 12.162 21.897 12.438L17.418 21.438C17.045 22.187 15.955 22.187 15.582 21.438L14.25 18.761ZM9.75 5.239L8.418 2.562C8.045 1.813 6.955 1.813 6.582 2.562L2.103 11.562C1.966 11.838 1.966 12.162 2.103 12.438L6.582 21.438C6.955 22.187 8.045 22.187 8.418 21.438L9.75 18.761");
}

</style>
