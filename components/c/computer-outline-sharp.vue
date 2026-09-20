<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1f35lbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:computer-outline-sharp" /></template>
<style>
.t1f35lbmf {
  fill: currentColor;
  d: path("M1.77 19.462v-1h20.46v1zm1.23-2v-13h18v13zm1-1h16v-11H4zm0 0v-11z");
}

</style>
