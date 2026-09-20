<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu_mmrkey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:download-done-sharp" /></template>
<style>
.fu_mmrkey {
  fill: currentColor;
  d: path("m9.55 15.192l-4.579-4.578l.713-.714l3.866 3.866L18.316 5l.713.714zM6 19v-1h12v1z");
}

</style>
