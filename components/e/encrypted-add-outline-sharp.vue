<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b22j6-bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:encrypted-add-outline-sharp" /></template>
<style>
.b22j6-bxc {
  fill: currentColor;
  d: path("M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615v5.688q0 .133-.012.28h-1q.006-.147.009-.28q.003-.132.003-.28V6.375l-6-2.23l-6 2.23V11.1q0 3.025 1.7 5.5t4.3 3.3zM17 21v-3h-3v-1h3v-3h1v3h3v1h-3v3zm-6.02-6.5h2.04l-.556-3.09q.442-.154.73-.545q.287-.392.287-.865q0-.61-.436-1.046t-1.047-.435t-1.045.435T10.519 10q0 .473.288.865q.287.39.73.544z");
}

</style>
