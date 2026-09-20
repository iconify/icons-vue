<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6bwznxdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-to-action-outline-sharp" /></template>
<style>
.d6bwznxdk {
  fill: currentColor;
  d: path("M6 17h12v-3H6zm-4 3V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
