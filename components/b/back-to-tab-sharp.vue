<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="focs3jbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:back-to-tab-sharp" /></template>
<style>
.focs3jbxu {
  fill: currentColor;
  d: path("M8.275 11.7L4 7.425V11H2V4h7v2H5.4l4.3 4.275zM2 20v-7h2v5h8v2zm18-7V6h-9V4h11v9zm2 2v5h-8v-5z");
}

</style>
