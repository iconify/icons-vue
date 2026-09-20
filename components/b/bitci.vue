<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1xw-9f6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bitci" /></template>
<style>
.m1xw-9f6o {
  fill: var(--svg-color--ff4802, #ff4802);
  fill-rule: evenodd;
  d: path("M6.939 3H9.75v.563h1.688V3h2.812v.574a4.219 4.219 0 0 1 2.127 7.672a4.781 4.781 0 0 1-1.845 9.192h-.282V21h-2.81v-.562H9.75V21H6.94v-.562H4.69L8.064 16.5H6.376v-9h1.688L4.689 3.563h2.25zM9.75 6.938h2.813a1.688 1.688 0 0 1 0 3.375H9.75zm0 6.187h4.219a1.97 1.97 0 0 1 0 3.938H9.751z");
}

</style>
