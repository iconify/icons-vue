<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sig0k-bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-weight-outline-sharp" /></template>
<style>
.sig0k-bdd {
  fill: currentColor;
  d: path("M5.5 18.27v-.5h13v.5zm0-2.5v-1h13v1zm0-3v-1.462h13v1.461zm0-3.5V5.73h13v3.54z");
}

</style>
