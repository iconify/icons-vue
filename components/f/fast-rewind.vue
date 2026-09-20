<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n32iw0bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fast-rewind" /></template>
<style>
.n32iw0bmf {
  fill: currentColor;
  d: path("m21.5 18l-9-6l9-6zm-10 0l-9-6l9-6z");
}

</style>
