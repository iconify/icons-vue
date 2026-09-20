<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go__qachx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-control-key-rounded" /></template>
<style>
.go__qachx {
  fill: currentColor;
  d: path("M12 7.825L7.1 12.7q-.275.275-.687.288T5.7 12.7q-.275-.275-.275-.7t.275-.7l5.6-5.6q.3-.3.7-.3t.7.3l5.6 5.6q.275.275.288.688t-.288.712q-.275.275-.7.275t-.7-.275z");
}

</style>
