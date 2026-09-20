<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9yikdbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:custom-typography-sharp" /></template>
<style>
.y9yikdbae {
  fill: currentColor;
  d: path("M11.5 21v-5h1v2H20v1h-7.5v2zM4 19v-1h5.116v1zm3.444-4.615H8.5l1.062-3.018h4.882l1.056 3.018h1.056L12.44 3h-.88zm2.448-3.954l2.058-5.802h.1l2.058 5.802z");
}

</style>
