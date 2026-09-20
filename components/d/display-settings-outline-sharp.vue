<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcbe0qfpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:display-settings-outline-sharp" /></template>
<style>
.hcbe0qfpt {
  fill: currentColor;
  d: path("M7.5 15H9v-4H7.5v1.25H6v1.5h1.5zm2.5-1.25h8v-1.5h-8zM15 11h1.5V9.75H18v-1.5h-1.5V7H15zM6 9.75h8v-1.5H6zM8 21v-2H2V3h20v16h-6v2zm-4-4h16V5H4zm0 0V5z");
}

</style>
