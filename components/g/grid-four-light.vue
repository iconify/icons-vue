<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uc0jyhbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:grid-four-light" /></template>
<style>
.uc0jyhbxb {
  fill: currentColor;
  d: path("M200 42H56a14 14 0 0 0-14 14v144a14 14 0 0 0 14 14h144a14 14 0 0 0 14-14V56a14 14 0 0 0-14-14m2 14v66h-68V54h66a2 2 0 0 1 2 2M56 54h66v68H54V56a2 2 0 0 1 2-2m-2 146v-66h68v68H56a2 2 0 0 1-2-2m146 2h-66v-68h68v66a2 2 0 0 1-2 2");
}

</style>
