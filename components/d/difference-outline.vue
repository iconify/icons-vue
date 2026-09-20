<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drb9mlbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:difference-outline" /></template>
<style>
.drb9mlbrb {
  fill: currentColor;
  d: path("M12.5 11h2V9h2V7h-2V5h-2v2h-2v2h2zm-2 4h6v-2h-6zM8 19q-.825 0-1.412-.587T6 17V3q0-.825.588-1.412T8 1h7l6 6v10q0 .825-.587 1.413T19 19zm0-2h11V8l-5-5H8zm-4 6q-.825 0-1.412-.587T2 21V7h2v14h11v2zm4-6V3z");
}

</style>
