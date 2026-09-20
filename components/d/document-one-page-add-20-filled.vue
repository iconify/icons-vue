<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1ggn4bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-one-page-add-20-filled" /></template>
<style>
.l1ggn4bsj {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5.207A5.5 5.5 0 0 0 14.5 9a5.5 5.5 0 0 0-3.163 1H7.5a.5.5 0 0 0 0 1h2.757a5.48 5.48 0 0 0-1.254 3.675A5.48 5.48 0 0 0 10.257 18H6a2 2 0 0 1-2-2zm8.5 2h-5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1m2 13a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a.5.5 0 0 1 .5.5V14h1.5a.5.5 0 0 1 0 1H15v1.5a.5.5 0 0 1-1 0V15h-1.5a.5.5 0 0 1 0-1H14v-1.5a.5.5 0 0 1 .5-.5");
}

</style>
