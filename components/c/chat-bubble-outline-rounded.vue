<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8ur0-b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-bubble-outline-rounded" /></template>
<style>
.p8ur0-b2i {
  fill: currentColor;
  d: path("m6 18l-2.3 2.3q-.475.475-1.088.213T2 19.575V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm-.85-2H20V4H4v13.125zM4 16V4z");
}

</style>
