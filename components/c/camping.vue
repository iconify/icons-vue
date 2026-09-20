<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g13dinb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camping" /></template>
<style>
.g13dinb0p {
  fill: currentColor;
  d: path("M3 21.5v-3.842l8.385-11.281l-1.135-1.504l.812-.604L12 5.548l.958-1.279l.792.604l-1.115 1.504L21 17.657V21.5zm4.879-1h8.242L12 14.725z");
}

</style>
