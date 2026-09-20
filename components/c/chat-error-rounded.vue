<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar0cbshva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-error-rounded" /></template>
<style>
.ar0cbshva {
  fill: currentColor;
  d: path("m6 18l-2.3 2.3q-.475.475-1.088.213T2 19.575V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm6-6.6l1.9 1.9q.275.275.7.275t.7-.275t.275-.7t-.275-.7L13.4 10l1.9-1.9q.275-.275.275-.7t-.275-.7t-.7-.275t-.7.275L12 8.6l-1.9-1.9q-.275-.275-.7-.275t-.7.275t-.275.7t.275.7l1.9 1.9l-1.9 1.9q-.275.275-.275.7t.275.7t.7.275t.7-.275z");
}

</style>
