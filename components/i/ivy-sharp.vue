<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejahclc3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ivy-sharp" /></template>
<style>
.ejahclc3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.32 12.25l1.2.28l.58.14l.43-.42l.57-.57l.43-.42l.27.53l.75 1.48l.27.54l-.49.35l-.34.24l-.49.35l-.16.58l-.11.41l-.17.57l-.59-.07l-1.65-.2l-.59-.07l.25-.54l.34-.74l.25-.54l-.33-.51l-.67-1.02l-.33-.5zm13.61-3.88l-.67 1.02l-.33.51l.25.54l.34.74l.25.54l-.59.07l-1.65.2l-.59.07l-.17-.57l-.11-.41l-.16-.58l-.49-.35l-.34-.24l-.49-.35l.27-.54l.75-1.48l.27-.53l.43.42l.57.57l.43.42l.58-.14l1.2-.28l.58-.13zM5.32 3.75l1.2.28l.58.14l.43-.42l.57-.57l.43-.42l.27.53l.75 1.48l.27.54l-.49.35l-.34.24l-.49.35l-.16.58l-.11.41l-.17.57l-.59-.07l-1.65-.2l-.59-.07l.25-.54l.34-.74l.25-.54l-.33-.51l-.67-1.02l-.33-.5zM12 21.25V3.5M12 17l-3.5-2.25m3.5-2l3.5-2.25m-3.5-2L8.5 6.25");
}

</style>
