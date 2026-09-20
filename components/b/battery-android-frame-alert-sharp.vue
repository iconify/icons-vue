<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g842qjb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-alert-sharp" /></template>
<style>
.g842qjb_n {
  fill: currentColor;
  d: path("M20.48 16.02q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.02-2.904V7.5h1v5.616zM2 17V7h16.116v1H3v8h15.154q.038.287.126.53t.226.47zm2.385-2.384V9.385h13.73v5.23z");
}

</style>
