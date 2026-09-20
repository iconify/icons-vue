<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdcb8ubbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:amp-stories-outline" /></template>
<style>
.jdcb8ubbp {
  fill: currentColor;
  d: path("M8 19V5h8v14zm-3.385-2V7h1v10zm13.77 0V7h1v10zM9 18h6V6H9zm0 0V6z");
}

</style>
