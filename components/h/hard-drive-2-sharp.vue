<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lizxz1tot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hard-drive-2-sharp" /></template>
<style>
.lizxz1tot {
  fill: currentColor;
  d: path("M13.923 18.616q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.229t-.54.23t-.23.54q0 .309.23.539t.54.23m2.923 0q.31 0 .54-.23t.23-.54t-.23-.54q-.23-.229-.54-.229t-.54.23t-.229.54t.23.539t.54.23M4 13.5V3h16v10.5zM4 21v-6.5h16V21z");
}

</style>
