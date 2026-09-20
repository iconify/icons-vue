<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5l92z_cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fit-page-width-sharp" /></template>
<style>
.g5l92z_cb {
  fill: currentColor;
  d: path("M8.808 14.539V9.46L6.269 12zM17.73 12l-2.539-2.539v5.078zM3 19V5h18v14z");
}

</style>
