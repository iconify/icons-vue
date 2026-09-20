<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a53a2lbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-off-sharp" /></template>
<style>
.a53a2lbtz {
  fill: currentColor;
  d: path("M18.925 16.075L6.85 4H16l6 8zM20.5 23.3L17.2 20H2V4.8L.7 3.5l1.4-1.4l19.8 19.8z");
}

</style>
