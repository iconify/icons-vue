<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfjukmz9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-arrow-up-rounded" /></template>
<style>
.dfjukmz9x {
  fill: currentColor;
  d: path("m12 10.8l-3.9 3.9q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7l4.6-4.6q.3-.3.7-.3t.7.3l4.6 4.6q.275.275.275.7t-.275.7t-.7.275t-.7-.275z");
}

</style>
