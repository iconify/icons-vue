<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aplpo1bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-arrow-up" /></template>
<style>
.aplpo1bbg {
  fill: currentColor;
  d: path("M18.885 19V6.916L17.4 8.4l-.708-.708L19.385 5l2.692 2.692l-.713.708l-1.48-1.479V19zM4 17.116v-3.21l7.375-7.273q.485-.466 1.159-.46t1.133.49l.931.943q.46.479.457 1.15t-.482 1.13l-7.325 7.23zm8.456-6.552l1.404-1.391q.192-.173.192-.432q0-.26-.192-.452l-.937-.937q-.173-.173-.423-.173t-.442.173l-1.43 1.404z");
}

</style>
