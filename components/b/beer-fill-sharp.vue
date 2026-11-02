<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0iivhwea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:beer-fill-sharp" /></template>
<style>
.l0iivhwea {
  fill: currentColor;
  d: path("M2.465 8a4.3 4.3 0 0 1 .005-2.128c.291-1.111 1.025-2.07 1.975-2.704C6.19 2.005 8.42 2.043 10 3.472c1.58-1.429 3.81-1.467 5.555-.304c.471.312.885.703 1.223 1.156c.349.462.604.988.752 1.548c.18.697.182 1.429.005 2.128ZM17 10v1a4 4 0 0 1 0 8v2a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10Zm-8 3a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm4 0a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm4 0v4a2 2 0 1 0 0-4");
}

</style>
