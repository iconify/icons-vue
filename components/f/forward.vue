<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8twl3rcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:forward" /></template>
<style>
.f8twl3rcu {
  fill: currentColor;
  d: path("M12 8V4l8 8l-8 8v-4H4V8z");
}

</style>
