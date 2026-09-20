<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4j75xs4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-one-outline-sharp" /></template>
<style>
.o4j75xs4y {
  fill: currentColor;
  d: path("M12 17h2V7h-4v2h2zm9 4H3V3h18zM5 19h14V5H5zM5 5v14z");
}

</style>
