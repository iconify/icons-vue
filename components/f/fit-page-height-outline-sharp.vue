<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn8dgd2ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-page-height-outline-sharp" /></template>
<style>
.hn8dgd2ky {
  fill: currentColor;
  d: path("M9 9h6l-3-3zm3 9l3-3H9zm8 4H4V2h16zm-2-2V4H6v16zm0-16H6z");
}

</style>
