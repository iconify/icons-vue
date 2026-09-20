<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckfgz8brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:insert-page-break-sharp" /></template>
<style>
.ckfgz8brw {
  fill: currentColor;
  d: path("M4 22v-5h16v5zm9-13h5l-5-5zm-4 6v-2h6v2zm8 0v-2h6v2zM1 15v-2h6v2zm3-4V2h10l6 6v3z");
}

</style>
