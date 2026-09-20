<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zunvsibum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:badge-outline-sharp" /></template>
<style>
.zunvsibum {
  fill: currentColor;
  d: path("M6.308 17.423h5.384v-.142q0-.34-.186-.63t-.521-.451q-.481-.206-.974-.309q-.494-.103-1.011-.103t-1.01.103t-.975.309q-.334.16-.52.45t-.187.63zM14 15.885h4V15h-4zm-4.159-1.231q.351-.347.351-.842t-.346-.846t-.842-.35t-.845.346t-.351.841t.346.846t.841.351t.846-.347M14 13.5h4v-.885h-4zM3 21V8h7V3h4v5h7v13zm1-1h16V9h-6v1.77h-4V9H4zm7-10.23h2V4h-2zm1 4.73");
}

</style>
