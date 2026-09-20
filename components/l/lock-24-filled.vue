<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d94ns-bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-24-filled" /></template>
<style>
.d94ns-bhj {
  d: path("M12 2a4 4 0 0 1 4 4v2h2.5A1.5 1.5 0 0 1 20 9.5v11a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 4 20.5v-11A1.5 1.5 0 0 1 5.5 8H8V6a4 4 0 0 1 4-4zm0 11.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3zM12 4a2 2 0 0 0-2 2v2h4V6a2 2 0 0 0-2-2z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
