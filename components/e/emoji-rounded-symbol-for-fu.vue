<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m_odamb7r"/><path class="k-ox03dns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-rounded-symbol-for-fu" /></template>
<style>
.k-ox03dns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24c0 11.874 9.626 21.5 21.5 21.5S45.5 35.874 45.5 24S35.874 2.5 24 2.5S2.5 12.126 2.5 24");
}

.m_odamb7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.304 6.493a17.66 17.66 0 0 1 11.057 5.99M26.304 41.507a17.66 17.66 0 0 0 15.203-15.203H26.304zm0-9.06h13.053m-8.446-6.143v13.821m-4.607-18.429h15.203a17.7 17.7 0 0 0-2.073-6.143h-13.13zm-4.608-4.606V6.492A17.66 17.66 0 0 0 7.645 17.089m14.051 24.418v-19.81H6.493a17.66 17.66 0 0 0 1.382 9.214m6.911-9.215v17.277");
}

</style>
