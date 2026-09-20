<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dan1rdbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dpay" /></template>
<style>
.dan1rdbpu {
  fill: var(--svg-color--7859e5, #7859e5);
  d: path("M15.938 13.125a5.175 5.175 0 0 1-4.979 3.938H4.125V21h6.834a9 9 0 0 0 8.916-7.875zM4.124 3h6.834a9 9 0 0 1 8.916 7.875h-3.937a5.175 5.175 0 0 0-4.979-3.937H4.125zm0 6.188h3.938v1.687H4.124zm0 3.937h3.938v1.688H4.124z");
}

</style>
