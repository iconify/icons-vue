<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwuigck9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hallway-outline-sharp" /></template>
<style>
.iwuigck9q {
  fill: currentColor;
  d: path("M4 21V5h4.885L12 1.885L15.116 5H20v16zm1-1h14V6H5zm2.5-2.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM10.139 5h3.723L12 3.139zM5 20V6z");
}

</style>
