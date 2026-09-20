<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhe0glbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:difference-sharp" /></template>
<style>
.vhe0glbcl {
  fill: currentColor;
  d: path("M12.5 11h2V9h2V7h-2V5h-2v2h-2v2h2zm-2 4h6v-2h-6zM6 19V1h9l6 6v12zm-4 4V7h2v14h11v2z");
}

</style>
