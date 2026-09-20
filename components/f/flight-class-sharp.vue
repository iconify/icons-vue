<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvxojhsim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flight-class-sharp" /></template>
<style>
.lvxojhsim {
  fill: currentColor;
  d: path("M12 13V4h6v9zm6 5H8L5 8V4h2v4l2.5 8H18zM8 21v-2h10v2z");
}

</style>
