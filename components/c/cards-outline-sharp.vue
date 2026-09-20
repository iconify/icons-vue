<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkfb1nrmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cards-outline-sharp" /></template>
<style>
.rkfb1nrmk {
  fill: currentColor;
  d: path("M6.77 11.116V6.769h4.346v4.347zm0 6.115v-4.347h4.346v4.347zm6.115-6.116V6.77h4.346v4.347zm0 6.116v-4.347h4.346v4.347zm-5.116-7.116h2.346V7.77H7.77zm6.116 0h2.346V7.77h-2.347zm-6.116 6.116h2.346v-2.347H7.77zm6.116 0h2.346v-2.347h-2.347zM4 20V4h16v16zm1-1h14V5H5z");
}

</style>
