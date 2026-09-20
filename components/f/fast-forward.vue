<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1yx9iwrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fast-forward" /></template>
<style>
.a1yx9iwrv {
  fill: currentColor;
  d: path("M4.096 16.616V7.385L11.02 12zm8.885 0V7.385L19.904 12z");
}

</style>
