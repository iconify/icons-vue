<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v17-dzbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:files-sharp" /></template>
<style>
.v17-dzbpb {
  fill: currentColor;
  d: path("M3 19v-4.77h9.23V5H21v14zm0-5.058V7h6.942zm2.114-.711l6.117-6.117v6.117z");
}

</style>
