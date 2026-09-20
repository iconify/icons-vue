<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6_7142ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-forward-outline" /></template>
<style>
.z6_7142ta {
  fill: currentColor;
  d: path("M17.079 12.5H5v-1h12.079l-5.792-5.792L12 5l7 7l-7 7l-.713-.708z");
}

</style>
