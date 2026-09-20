<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g4kt-d-1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:expchain" /></template>
<style>
.g4kt-d-1q {
  fill: var(--svg-color--141413, #141413);
  fill-rule: evenodd;
  d: path("m13.465 3.837l6.408 10.988c.467.801.19 1.826-.62 2.288l-6.407 3.663a1.71 1.71 0 0 1-1.692 0l-6.408-3.663a1.666 1.666 0 0 1-.62-2.288l6.409-10.988c.651-1.116 2.279-1.116 2.93 0M5.364 15.532a.26.26 0 0 0 .096.356l6.178 3.531V4.775zm6.998-10.757v14.644l6.178-3.53a.26.26 0 0 0 .096-.357z");
}

</style>
