<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f9qmqlbpl"/><path class="whchebbjm"/><path class="iyj-0ob5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kick-scooter-line-duotone" /></template>
<style>
.f9qmqlbpl {
  stroke-linejoin: round;
  d: path("M6.76172 17.6471H14.3808C14.3808 14.7882 16.7259 12.4706 19.6189 12.4706L18.6147 6.51663C18.4639 5.62255 18.3885 5.1755 18.1628 4.84003C17.9638 4.54431 17.6842 4.31026 17.3563 4.1649C16.9844 4 16.5258 4 15.6086 4H14.3808");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyj-0ob5o {
  d: path("M22.0002 17.6471C22.0002 18.9466 20.9342 20.0001 19.6192 20.0001C18.3043 20.0001 17.2383 18.9466 17.2383 17.6471C17.2383 16.3476 18.3043 15.2942 19.6192 15.2942C20.9342 15.2942 22.0002 16.3476 22.0002 17.6471Z");
}

.whchebbjm {
  d: path("M6.7619 17.6471C6.7619 18.9466 5.69592 20.0001 4.38095 20.0001C3.06599 20.0001 2 18.9466 2 17.6471C2 16.3476 3.06599 15.2942 4.38095 15.2942C5.69592 15.2942 6.7619 16.3476 6.7619 17.6471Z");
}

</style>
