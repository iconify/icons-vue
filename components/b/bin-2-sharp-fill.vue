<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvlqxfeer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-2-sharp-fill" /></template>
<style>
.gvlqxfeer {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 8L19 8L19 22C19 22.5523 18.5523 23 18 23L6 23C5.4477 23 5 22.5523 5 22L5 8L3 8L3 6L21 6L21 8ZM15 3L9 3L9 1L15 1L15 3ZM9 10L9 19L11 19L11 10L9 10ZM13 10L13 19L15 19L15 10L13 10Z");
}

</style>
