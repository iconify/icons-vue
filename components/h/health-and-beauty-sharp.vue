<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv0jw0ref"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:health-and-beauty-sharp" /></template>
<style>
.cv0jw0ref {
  fill: currentColor;
  d: path("M16 22v-2h4v-2h-4v-2h4v-2h-4v-2h4v-2h-4V8h4V6h-4V4h7v18zM5 22L1 11l5-3V2h4v6l5 3l-4 11z");
}

</style>
