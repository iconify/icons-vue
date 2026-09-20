<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrd9ksbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:delete-sweep" /></template>
<style>
.zrd9ksbqb {
  fill: currentColor;
  d: path("M14.885 17.5v-1h3v1zm0-8v-1h6v1zm0 4v-1h5v1zM4.115 8h-1V7h3.731v-.885h2.538V7h3.732v1h-1v8.385q0 .69-.463 1.153T10.5 18H5.73q-.69 0-1.152-.462t-.462-1.153z");
}

</style>
