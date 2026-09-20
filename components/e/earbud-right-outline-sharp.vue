<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_-o38ibr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:earbud-right-outline-sharp" /></template>
<style>
.q_-o38ibr {
  fill: currentColor;
  d: path("M12 22V12h-2v-2h4v10h2V10h3V6h-9V4h11v8h-3v10zm-3-8q-2.5 0-4.25-1.75T3 8t1.75-4.25T9 2h1v12zm-1-2.125v-7.75q-1.35.35-2.175 1.425T5 8t.825 2.45T8 11.875M8 8");
}

</style>
