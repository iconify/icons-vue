<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5mho0tup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:double-sharp" /></template>
<style>
.f5mho0tup {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25H4.5q-.932 0-1.591.659T2.25 4.5V6q0 2.25 2.25 2.25H6q.595 0 1.032-.157L10.939 12l-3.907 3.907Q6.595 15.75 6 15.75H4.5q-.932 0-1.591.659T2.25 18v1.5q0 2.25 2.25 2.25H6q2.25 0 2.25-2.25V18q0-.595-.157-1.032L12 13.061l3.907 3.907q-.157.437-.157 1.032v1.5q0 2.25 2.25 2.25h1.5q2.25 0 2.25-2.25V18q0-2.25-2.25-2.25H18q-.595 0-1.032.157L13.061 12l3.907-3.907q.437.157 1.032.157h1.5q2.25 0 2.25-2.25V4.5q0-2.25-2.25-2.25H18q-2.25 0-2.25 2.25V6q0 .595.157 1.032L12 10.939L8.093 7.032Q8.25 6.595 8.25 6V4.5q0-2.25-2.25-2.25");
}

</style>
