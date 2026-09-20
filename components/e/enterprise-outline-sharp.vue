<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l03zihsaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:enterprise-outline-sharp" /></template>
<style>
.l03zihsaj {
  fill: currentColor;
  d: path("M12 15q.633 0 1.066-.434q.434-.433.434-1.066t-.434-1.066T12 12t-1.066.434q-.434.433-.434 1.066t.434 1.066T12 15m-9 5V7h6V4h6v3h6v13zm1-1h16V8H4zm6-12h4V5h-4zM4 19V8z");
}

</style>
