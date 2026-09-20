<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl6c0abys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:co-present-sharp" /></template>
<style>
.zl6c0abys {
  fill: currentColor;
  d: path("M21 19.577V4.5H3v8H2v-9h20v16.077zm-14.123-7.07Q6 11.632 6 10.386t.877-2.123Q7.754 7.385 9 7.385t2.123.877t.877 2.123t-.877 2.123T9 13.385t-2.123-.877M2 20.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v1.646z");
}

</style>
