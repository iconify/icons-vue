<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1g338btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:card-membership-sharp" /></template>
<style>
.r1g338btr {
  fill: currentColor;
  d: path("M2 2h20v15h-6v5l-4-2l-4 2v-5H2zm2 11h16v-3H4z");
}

</style>
