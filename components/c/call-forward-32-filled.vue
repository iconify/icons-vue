<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w67699zkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-forward-32-filled" /></template>
<style>
.w67699zkv {
  fill: currentColor;
  d: path("M7.888 4.158c2.08-2.08 4.735-2.311 6.712-2.091c2.645.295 3.773 2.94 3.298 5.154l-.413 1.926a4 4 0 0 1-3.126 3.085l-2.68.536c-.06.103-.133.242-.208.423C11.25 13.722 11 14.625 11 16s.25 2.277.47 2.808q.116.27.208.424l2.68.536a4 4 0 0 1 3.127 3.084l.413 1.926c.475 2.214-.653 4.86-3.298 5.155c-1.977.22-4.632-.012-6.712-2.091c-1.17-1.17-2.133-2.979-2.804-5.02A22.2 22.2 0 0 1 4 16c0-2.383.407-4.763 1.084-6.822c.67-2.042 1.634-3.85 2.804-5.02m15.36 5.637a1 1 0 0 0-1.42 1.41L25.599 15H16a1 1 0 1 0 0 2h9.598l-3.77 3.795a1 1 0 0 0 1.42 1.41l5.462-5.5a1 1 0 0 0 0-1.41z");
}

</style>
