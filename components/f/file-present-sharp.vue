<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c94irjbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-present-sharp" /></template>
<style>
.c94irjbxq {
  fill: currentColor;
  d: path("M12 19q1.675 0 2.838-1.175T16 15v-4h-2v4q0 .825-.575 1.413T12 17q-.825 0-1.412-.587T10 15V9.5q0-.225.15-.363T10.5 9q.225 0 .363.138T11 9.5V15h2V9.5q0-1.05-.725-1.775T10.5 7t-1.775.725T8 9.5V15q0 1.65 1.175 2.825T12 19m-8 3V2h11l5 5v15zM14 4v4h4z");
}

</style>
