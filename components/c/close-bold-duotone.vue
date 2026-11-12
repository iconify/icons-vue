<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5jc2bad"/><path class="rjuy8dl9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:close-bold-duotone" /></template>
<style>
.ch5jc2bad {
  fill: currentColor;
  d: path("M5.53717 19.5302C5.24427 19.8231 4.7694 19.8231 4.47651 19.5302C4.18361 19.2373 4.18361 18.7624 4.47651 18.4696L18.4764 4.46967C18.7693 4.17678 19.2442 4.17678 19.5371 4.46967C19.8299 4.76256 19.8299 5.23744 19.5371 5.53033L5.53717 19.5302Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rjuy8dl9o {
  fill: currentColor;
  d: path("M4.46978 5.53045C4.17689 5.23756 4.17689 4.76269 4.46978 4.46979C4.76268 4.1769 5.23755 4.1769 5.53044 4.46979L19.5303 18.4697C19.8232 18.7626 19.8232 19.2374 19.5303 19.5303C19.2374 19.8232 18.7626 19.8232 18.4697 19.5303L4.46978 5.53045Z");
}

</style>
