<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3qno_b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-above-24-regular" /></template>
<style>
.s3qno_b4o {
  fill: currentColor;
  d: path("M20.25 9a.75.75 0 0 1 .75.75v8A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75v-8A.75.75 0 0 1 3.75 9zM4.5 17.75c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V10.5h-15zM20.25 3a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5z");
}

</style>
