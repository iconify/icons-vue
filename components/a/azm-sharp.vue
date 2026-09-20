<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg5ib972w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:azm-sharp" /></template>
<style>
.dg5ib972w {
  fill: currentColor;
  d: path("m15.904 15.5l2.904-2.904V5h-7.596L8.308 7.904h7.596zM11 20.404l2.904-2.904V9.904H6.308l-2.904 2.904H11z");
}

</style>
