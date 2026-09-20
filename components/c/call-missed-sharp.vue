<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx3y82b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-missed-sharp" /></template>
<style>
.dx3y82b7n {
  fill: currentColor;
  d: path("M12.096 16.714L5 9.616v5.287H4v-7h7v1H5.708l6.388 6.388l7.216-7.215l.707.714z");
}

</style>
