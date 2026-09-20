<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b08-0mbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-cafe-sharp" /></template>
<style>
.b08-0mbcp {
  fill: currentColor;
  d: path("M4 21v-2h16v2zm0-4V3h18v7h-4v7zm14-9h2V5h-2z");
}

</style>
