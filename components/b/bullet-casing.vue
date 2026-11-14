<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3zm_cbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bullet-casing" /></template>
<style>
.b3zm_cbow {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.75 8.737l1.836 2.294q.079.1.122.221q.042.12.042.248v6.922q1 .414 1 1.828q0 2-2 2h-7.5q-2 0-2-2q0-1.414 1-1.828V11.5q0-.128.042-.248q.043-.121.122-.221L9.25 8.737V6.5q0-4.75 2.75-4.75t2.75 4.75zm-1.5-.487V6.5q0-3.25-1.25-3.25T10.75 6.5v1.75z");
}

</style>
