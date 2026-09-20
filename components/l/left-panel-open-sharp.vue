<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl4eejpgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:left-panel-open-sharp" /></template>
<style>
.vl4eejpgx {
  fill: currentColor;
  d: path("M12.5 8v8l4-4zM10 19h9V5h-9zm-7 2V3h18v18z");
}

</style>
