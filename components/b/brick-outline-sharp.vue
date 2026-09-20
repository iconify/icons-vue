<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk23ogb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brick-outline-sharp" /></template>
<style>
.bk23ogb-s {
  fill: currentColor;
  d: path("M3 19V8.712h2.827V5h4.789v3.712h2.769V5h4.788v3.712H21V19zm1-1h16V9.712H4zm2.827-9.288h2.789V6H6.827zm7.558 0h2.788V6h-2.788zM4 18h16zm2.827-9.288h2.789zm7.558 0h2.788z");
}

</style>
