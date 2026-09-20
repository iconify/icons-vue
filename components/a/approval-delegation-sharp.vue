<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nji08ztfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:approval-delegation-sharp" /></template>
<style>
.nji08ztfs {
  fill: currentColor;
  d: path("m13.54 11.05l-3.538-3.539l.714-.688l2.825 2.825l5.675-5.65l.688.688zM3 21v-8.154h3V21zm11.616.808L7 19.583v-6.737h2.379l7.352 2.712v1.596h-3l-2.596-.925l-.312.752l2.87.942h7.923V19.5z");
}

</style>
