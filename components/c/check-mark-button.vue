<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z70tob8zk"/><path class="edmjdeb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:check-mark-button" /></template>
<style>
.edmjdeb6j {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M53.867 14.14a4.656 4.656 0 0 0-6.562.514l-20.04 23.437l-10.781-9a4.248 4.248 0 1 0-5.447 6.519l14.444 12.06a4.22 4.22 0 0 0 3.235.946A4.65 4.65 0 0 0 31.895 47l22.483-26.3a4.66 4.66 0 0 0-.515-6.562");
}

.z70tob8zk {
  fill: var(--svg-color--37b34a, #37b34a);
  d: path("M63.792 56.915a6.876 6.876 0 0 1-6.875 6.876H6.875A6.876 6.876 0 0 1 0 56.915V6.875A6.88 6.88 0 0 1 6.875 0h50.042a6.877 6.877 0 0 1 6.875 6.875z");
}

</style>
