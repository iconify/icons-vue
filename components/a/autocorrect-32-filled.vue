<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sn4237_kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autocorrect-32-filled" /></template>
<style>
.sn4237_kn {
  fill: currentColor;
  d: path("M15.165 7.903a1 1 0 0 1 1.67 0L20.187 13H19.5a6.5 6.5 0 1 0 5.6 3.198l-.04-.075l-.371-.623h4.061a1.25 1.25 0 1 0 0-2.5h-5.572l-4.253-6.47c-1.383-2.103-4.467-2.103-5.85 0L2.206 23.065a1.25 1.25 0 0 0 2.09 1.373zM15.5 19.5a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>
