<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3cypbbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-sharp" /></template>
<style>
.a3cypbbay {
  fill: currentColor;
  d: path("M15.192 19v-5.808H21V19zm-4-8.192V5H21v5.808zM3 19v-5.808h9.808V19zm0-8.192V5h5.808v5.808z");
}

</style>
