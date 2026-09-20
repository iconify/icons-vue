<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uitdnubas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-distribute-sharp" /></template>
<style>
.uitdnubas {
  fill: currentColor;
  d: path("M2 22V2h2v20zm8.5-5V7h3v10zm9.5 5V2h2v20z");
}

</style>
