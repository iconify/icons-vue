<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ak2v_tbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-micronesia" /></template>
<style>
.ak2v_tbux {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m3.13 21.586l-2.366-1.794l-2.364 1.794l.896-2.917l-2.355-1.81l2.916-.01l.908-2.911l.908 2.911l2.918.01l-2.356 1.81zm-4.731 16.826l2.364 1.796l2.366-1.796l-.896 2.919l2.356 1.808l-2.918.01l-.908 2.911l-.908-2.911l-2.916-.01l2.355-1.808zm12.452-7.5l-.908 2.912l-.908-2.912l-2.915-.01l2.354-1.809l-.895-2.918l2.364 1.794l2.364-1.794l-.895 2.918l2.354 1.809zm-23.159-4.736l2.364 1.794l2.364-1.794l-.895 2.918l2.355 1.809l-2.916.01l-.909 2.912l-.908-2.912l-2.916-.01l2.354-1.809z");
}

</style>
