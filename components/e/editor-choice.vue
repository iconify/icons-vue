<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8j5qvbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:editor-choice" /></template>
<style>
.v8j5qvbvt {
  fill: currentColor;
  d: path("M7.385 22v-6.956L3.962 9.5L7.972 3h8.057l4.01 6.5l-3.423 5.544V22L12 20.404zM8.519 4l-3.4 5.5l3.4 5.5h6.962l3.4-5.5l-3.4-5.5zm2.431 8.864L8.112 10.05l.713-.714l2.125 2.125l4.225-4.25l.713.689z");
}

</style>
