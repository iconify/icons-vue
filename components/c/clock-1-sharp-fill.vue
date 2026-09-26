<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brc0qgbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-1-sharp-fill" /></template>
<style>
.brc0qgbmq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM11 5L11 12.0001C11 13.0233 12.3545 13.3862 12.866 12.5001L15.6547 7.6699L13.9227 6.6699L13 8.268L13 5L11 5Z");
}

</style>
