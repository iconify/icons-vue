<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4nbftbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:graphene" /></template>
<style>
.w4nbftbur {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.707 7.866q.123.211.2.422q.217-.038.455-.038h1.776q1.292 0 1.944 1.116l.875 1.5q.661 1.134 0 2.268l-.875 1.5q-.652 1.116-1.944 1.116h-1.776q-.238 0-.455-.038q-.077.211-.2.422l-.875 1.5q-.652 1.116-1.944 1.116h-1.776q-1.292 0-1.944-1.116l-.875-1.5q-.123-.211-.2-.422q-.217.038-.455.038H5.862q-1.292 0-1.944-1.116l-.875-1.5q-.662-1.134 0-2.268l.875-1.5Q4.57 8.25 5.862 8.25h1.776q.238 0 .455.038q.077-.211.2-.422l.875-1.5Q9.82 5.25 11.112 5.25h1.776q1.292 0 1.944 1.116z");
}

</style>
