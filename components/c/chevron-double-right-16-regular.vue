<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zo3z3la_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-double-right-16-regular" /></template>
<style>
.zo3z3la_c {
  fill: currentColor;
  d: path("M3.646 3.146a.5.5 0 0 1 .707 0l4.5 4.5a.504.504 0 0 1 0 .708l-4.5 4.5a.5.5 0 0 1-.707-.707L7.793 8L3.646 3.854a.5.5 0 0 1 0-.708m4 0a.5.5 0 0 1 .708 0l4.5 4.5a.5.5 0 0 1 .136.45a.5.5 0 0 1-.136.258l-4.5 4.5a.5.5 0 0 1-.708-.707L11.793 8L7.646 3.854a.5.5 0 0 1 0-.708");
}

</style>
