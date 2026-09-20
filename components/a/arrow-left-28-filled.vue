<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wx7quizco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-left-28-filled" /></template>
<style>
.wx7quizco {
  fill: currentColor;
  d: path("M12.298 4.289a1 1 0 0 1 1.406 1.422L6.328 13h17.675a1 1 0 1 1 0 2H6.33l7.374 7.286a1 1 0 0 1-1.406 1.423l-8.927-8.821a1.25 1.25 0 0 1 0-1.778z");
}

</style>
