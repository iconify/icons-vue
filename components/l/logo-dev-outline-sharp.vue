<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a50-opdaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:logo-dev-outline-sharp" /></template>
<style>
.a50-opdaq {
  fill: currentColor;
  d: path("M6.192 14.692h2.589l.596-.615V9.904l-.596-.596H6.192zm.804-.803v-3.777h1.577v3.777zm4.125 0v-1.493h1.396v-.804h-1.396v-1.48h2.012v-.804h-2.816v5.384h2.816v-.803zm4.808-.193L14.68 9.308h-.854l1.479 5.379h1.227l1.46-5.38h-.854zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
