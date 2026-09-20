<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dxqm_aclw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-dismiss-16-regular" /></template>
<style>
.dxqm_aclw {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M5.586 2a1.5 1.5 0 0 1 1.06.44L8.207 4H12.5A2.5 2.5 0 0 1 15 6.5v.757a5.5 5.5 0 0 0-1-.656V6.5A1.5 1.5 0 0 0 12.5 5H8.207l-1.56 1.56A1.5 1.5 0 0 1 5.585 7H2v4.5A1.5 1.5 0 0 0 3.5 13h2.708q.149.524.394 1H3.5A2.5 2.5 0 0 1 1 11.5v-7A2.5 2.5 0 0 1 3.5 2zm7.768 7.646a.5.5 0 0 0-.707 0L11.5 10.793l-1.146-1.147a.5.5 0 1 0-.708.707l1.147 1.147l-1.147 1.146a.5.5 0 1 0 .707.707l1.147-1.146l1.146 1.146a.5.5 0 1 0 .707-.707L12.208 11.5l1.146-1.146a.5.5 0 0 0 0-.708M3.5 3A1.5 1.5 0 0 0 2 4.5V6h3.586a.5.5 0 0 0 .353-.146L7.293 4.5L5.939 3.146A.5.5 0 0 0 5.586 3z");
}

</style>
