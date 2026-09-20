<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ni89s_bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:heavy-plus-sign" /></template>
<style>
.ni89s_bna {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M127.35 59.61c0-4.36-3.56-7.92-7.92-7.92h-35.2c-4.36 0-7.92-3.56-7.92-7.92V8.57c0-4.36-3.56-7.92-7.92-7.92h-8.78c-4.36 0-7.92 3.56-7.92 7.92v35.19c0 4.36-3.56 7.92-7.92 7.92H8.57c-4.36 0-7.92 3.56-7.92 7.92v8.79c0 4.36 3.56 7.92 7.92 7.92h35.2c4.36 0 7.92 3.56 7.92 7.92v35.19c0 4.36 3.56 7.92 7.92 7.92h8.78c4.36 0 7.92-3.56 7.92-7.92V84.23c0-4.36 3.56-7.92 7.92-7.92h35.2c4.36 0 7.92-3.56 7.92-7.92z");
}

</style>
