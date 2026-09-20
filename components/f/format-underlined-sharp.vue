<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blg59tb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-underlined-sharp" /></template>
<style>
.blg59tb1o {
  fill: currentColor;
  d: path("M5 21v-2h14v2zm3.075-5.575q-1.4-1.575-1.4-4.175V3H9.25v8.4q0 1.4.7 2.275t2.05.875t2.05-.875t.7-2.275V3h2.575v8.25q0 2.6-1.4 4.175T12 17t-3.925-1.575");
}

</style>
