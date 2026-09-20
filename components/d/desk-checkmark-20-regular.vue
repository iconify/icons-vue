<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n9kyjwbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-checkmark-20-regular" /></template>
<style>
.n9kyjwbei {
  fill: currentColor;
  d: path("M9.208 4a5.5 5.5 0 0 0-.185 1H4a1 1 0 0 0-1 1v1h6.208c.17.602.44 1.161.792 1.66V14a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zM18 15.5a.5.5 0 0 1-1 0v-5.102a5.5 5.5 0 0 0 1-.656zM3 14a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V8H3zm4-4.5a.5.5 0 0 1 0 1H5a.5.5 0 0 1 0-1zM14.5 1a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m2.354 2.646a.5.5 0 0 0-.707 0L13.5 6.293l-.646-.647a.5.5 0 1 0-.707.708l1 1a.5.5 0 0 0 .707 0l3-3a.5.5 0 0 0 0-.708");
}

</style>
