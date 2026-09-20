<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu07j0b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:breakfast-dining-sharp" /></template>
<style>
.mu07j0b4s {
  fill: currentColor;
  d: path("M4 21V10.45q-.925-.55-1.463-1.462T2 7q0-1.65 1.175-2.825T6 3h12q1.65 0 2.825 1.175T22 7q0 1.075-.537 1.988T20 10.45V21zm8-3.6l4.4-4.4L12 8.6L7.6 13zm0-2.8L10.4 13l1.6-1.6l1.6 1.6z");
}

</style>
