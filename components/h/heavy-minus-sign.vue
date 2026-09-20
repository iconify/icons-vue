<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kxc0eacnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:heavy-minus-sign" /></template>
<style>
.kxc0eacnd {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M8.57 51.69c-4.36 0-7.92 3.56-7.92 7.92v8.78c0 4.36 3.56 7.92 7.92 7.92h110.86c4.36 0 7.92-3.56 7.92-7.92v-8.78c0-4.36-3.56-7.92-7.92-7.92z");
}

</style>
