<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5i24ob8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:contrast-bold" /></template>
<style>
.b5i24ob8h {
  fill: currentColor;
  d: path("M12 2C17.5228 2 22 6.477 22 12C22 17.523 17.5228 22 12 22C6.4772 22 2 17.523 2 12C2 6.477 6.4772 2 12 2ZM12 20.5C16.6944 20.5 20.5 16.694 20.5 12C20.5 7.306 16.6944 3.5 12 3.5V20.5Z");
}

</style>
