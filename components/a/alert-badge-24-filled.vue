<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iolxzm95k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:alert-badge-24-filled" /></template>
<style>
.iolxzm95k {
  fill: currentColor;
  d: path("M18.5 9q.508-.002.973-.137q.027.317.027.64v4l1.418 3.16A.95.95 0 0 1 20.052 18h-16.1a.95.95 0 0 1-.867-1.338l1.415-3.16V9.49l.005-.25a7.5 7.5 0 0 1 11.43-6.123A3.5 3.5 0 0 0 18.5 9m-3.542 10.003a3 3 0 0 1-5.916 0zM18.5 8a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

</style>
