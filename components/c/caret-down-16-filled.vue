<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ngrgeeg2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-down-16-filled" /></template>
<style>
.ngrgeeg2f {
  fill: currentColor;
  d: path("M4.957 5a1 1 0 0 0-.821 1.571l2.633 3.784a1.5 1.5 0 0 0 2.462 0l2.633-3.784A1 1 0 0 0 11.043 5z");
}

</style>
