<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7xop0bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:list-arrow-sharp" /></template>
<style>
.b7xop0bee {
  fill: currentColor;
  d: path("m6 20l-4-4l1.4-1.4L5 16.15V5h2v11.15l1.6-1.55L10 16zm6-1v-2h10v2zm0-6v-2h10v2zm0-6V5h10v2z");
}

</style>
