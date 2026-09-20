<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":232};
const content = `<path class="d7xarjb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:css-3-official" /></template>
<style>
.d7xarjb-e {
  fill: var(--svg-color--444, #444);
  d: path("m100.902 231.618l116.456-38.653L256 0H37.867L29.57 43.056h174.812l-5.443 27.49H23.862L15.3 113.602h174.823l-9.602 49.284l-70.547 23.076l-60.955-23.076l4.16-21.528H10.123L0 192.965z");
}

</style>
