<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm8guo8vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-export-outline" /></template>
<style>
.zm8guo8vy {
  fill: currentColor;
  d: path("m5.05 22.375l-1.4-1.425L6.6 18H4.35v-2H10v5.65H8v-2.225zM12 22v-2h6V9h-5V4H6v10H4V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22z");
}

</style>
