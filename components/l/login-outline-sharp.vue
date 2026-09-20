<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqhgepihe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:login-outline-sharp" /></template>
<style>
.mqhgepihe {
  fill: currentColor;
  d: path("M12 21v-2h7V5h-7V3h9v18zm-2-4l-1.375-1.45l2.55-2.55H3v-2h8.175l-2.55-2.55L10 7l5 5z");
}

</style>
