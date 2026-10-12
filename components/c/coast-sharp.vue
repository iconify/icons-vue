<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="memc76-bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coast-sharp" /></template>
<style>
.memc76-bg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.8 2.75h14.45V18l-.75-.27l-1.25-.46l-.75-.27l-.33-.73l-.59-1.29l-.33-.73l-.76-.24l-1.73-.52l-.76-.24l-.18-.78l-.39-1.69l-.18-.78l-.78-.18l-1.69-.39l-.78-.18l-.18-.78l-.39-1.69L9.25 6l-.78-.17l-.69-.16L7 5.5l-.27-.75l-.46-1.25L6 2.75zm-4.05 8l2.143.357l.357 2.143l.357 2.143l2.143.357l2.143.357l.357 2.143l.357 2.143l2.143.357");
}

</style>
