<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqke1hhpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-up-24-filled" /></template>
<style>
.uqke1hhpk {
  fill: currentColor;
  d: path("M12.707 2.293a1 1 0 0 0-1.414 0l-5 5a1 1 0 0 0 1.414 1.414L11 5.414V18a1 1 0 1 0 2 0V5.414l3.293 3.293a1 1 0 1 0 1.414-1.414zM5.25 20.5a.75.75 0 0 0 0 1.5h13.5a.75.75 0 0 0 0-1.5z");
}

</style>
