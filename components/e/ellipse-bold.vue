<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogb3bzttz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ellipse-bold" /></template>
<style>
.ogb3bzttz {
  fill: currentColor;
  d: path("M12 19C17.5228 19 22 15.866 22 12C22 8.13401 17.5228 5 12 5C6.47715 5 2 8.13401 2 12C2 15.866 6.47715 19 12 19Z");
}

</style>
