<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phvfsomdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ain" /></template>
<style>
.phvfsomdq {
  fill: var(--svg-color--663fbc, #663fbc);
  d: path("M11.4 3v5.91L7.698 14.4H3v-.6L10.8 3zm.6 0v5.904l3.942 5.496H21v-.6L12.6 3zm9 12h-4.626l4.302 6H21zm-1.062 6l-4.302-6h-7.62l-4.044 6zM3.252 21l4.044-6H3v6zm5.172-6.6l3.282-4.872l3.498 4.872z");
}

</style>
