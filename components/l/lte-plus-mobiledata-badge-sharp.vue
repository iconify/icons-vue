<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d25b_nquv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lte-plus-mobiledata-badge-sharp" /></template>
<style>
.d25b_nquv {
  fill: currentColor;
  d: path("M4 16h4v-2H6V8H4zm5.5 0h2v-6H13V8H8v2h1.5zm4.5 0h4v-2h-2v-1h1.5v-2H16v-1h2V8h-4zM1 21V3h22v8.25h-1.25V10h-1.5v1.25H19v1.5h1.25V14h1.5v-1.25H23V21z");
}

</style>
