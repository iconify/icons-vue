<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2drqtb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:domain-verification-outline-sharp" /></template>
<style>
.k2drqtb5a {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V8H4zm6.95-2.18l-2.858-2.858l.72-.72l2.138 2.139l4.239-4.239l.719.72zM4 18V6z");
}

</style>
