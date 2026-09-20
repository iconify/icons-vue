<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_3bjabbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-2-sharp" /></template>
<style>
.v_3bjabbk {
  fill: currentColor;
  d: path("M15 20v-7h7v7zm-4-9V4h11v7zm-9 9v-7h11v7zm0-9V4h7v7z");
}

</style>
