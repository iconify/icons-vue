<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idnli9-1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:campaign-outline-sharp" /></template>
<style>
.idnli9-1m {
  fill: currentColor;
  d: path("M18 13v-2h4v2zm1.2 7L16 17.6l1.2-1.6l3.2 2.4zm-2-12L16 6.4L19.2 4l1.2 1.6zM5 19v-4H2V9h6l5-3v12l-5-3H7v4zm6-4.55v-4.9L8.55 11H4v2h4.55zm3 .9v-6.7q.675.6 1.088 1.463T15.5 12t-.413 1.888T14 15.35M7.5 12");
}

</style>
