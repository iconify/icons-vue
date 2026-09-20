<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm7cgpbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fluorescent-sharp" /></template>
<style>
.cm7cgpbyb {
  fill: currentColor;
  d: path("M5 15.05v-6h14v6zM11 5V2h2v3zm7.7 2.8l-1.4-1.4l1.8-1.8L20.5 6zM11 22v-3h2v3zm8.1-2.5l-1.8-1.8l1.4-1.4l1.8 1.8zM5.3 7.8L3.5 6l1.4-1.4l1.8 1.8zm-.4 11.7l-1.4-1.4l1.8-1.8l1.4 1.4z");
}

</style>
