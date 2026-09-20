<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbbfu-92e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hov-sharp" /></template>
<style>
.qbbfu-92e {
  fill: currentColor;
  d: path("M12 22L6 12l6-10l6 10z");
}

</style>
