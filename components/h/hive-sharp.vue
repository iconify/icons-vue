<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zquwoz4xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hive-sharp" /></template>
<style>
.zquwoz4xw {
  fill: currentColor;
  d: path("M15.948 11.616L14.325 8.71l1.623-2.903h3.196l1.623 2.903l-1.623 2.904zm-5.546 3.288L8.779 12l1.623-2.904h3.196L15.221 12l-1.623 2.904zm0-6.596L8.779 5.404L10.402 2.5h3.196l1.623 2.904l-1.623 2.904zm-5.546 3.308L3.233 8.712l1.623-2.904h3.196l1.606 2.904l-1.606 2.904zm0 6.576L3.233 15.29l1.623-2.904h3.196l1.606 2.904l-1.606 2.903zm5.569 3.308l-1.646-2.904l1.623-2.904h3.196l1.623 2.904l-1.623 2.904zm5.523-3.308l-1.623-2.904l1.623-2.904h3.196l1.623 2.904l-1.623 2.904z");
}

</style>
