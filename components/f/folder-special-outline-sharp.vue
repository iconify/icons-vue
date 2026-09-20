<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebb-pdgwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-special-outline-sharp" /></template>
<style>
.ebb-pdgwp {
  fill: currentColor;
  d: path("m13.023 16.104l1.877-1.442l1.877 1.442l-.696-2.331l1.896-1.542h-2.33L14.9 9.95l-.746 2.28h-2.331l1.896 1.543zM3 19V5h6.596l2 2H21v12zm1-1h16V8h-8.806l-2-2H4zm0 0V6z");
}

</style>
