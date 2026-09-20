<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh4sj0gje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:developer-guide-outline-sharp" /></template>
<style>
.nh4sj0gje {
  fill: currentColor;
  d: path("M4 20V4h16v16zM5 5v14h14V5h-2.5v6.116l-2-1.193l-2 1.193V5zm0 14V5z");
}

</style>
