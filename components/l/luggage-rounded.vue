<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxpad6bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:luggage-rounded" /></template>
<style>
.qxpad6bcb {
  fill: currentColor;
  d: path("M7.462 20q-.667 0-1.141-.475t-.475-1.14V8q0-.666.475-1.14q.474-.476 1.14-.476h2.155V4.615q0-.666.474-1.14T11.23 3h1.54q.666 0 1.14.475t.475 1.14v1.77h2.154q.666 0 1.14.474q.475.475.475 1.141v10.385q0 .666-.475 1.14T16.54 20v.23q0 .31-.23.54t-.54.23t-.54-.23t-.229-.54V20H9v.23q0 .31-.23.54t-.54.23t-.539-.23t-.23-.54zM9.759 9.298q-.144.143-.144.356v7.077q0 .212.144.356t.357.144t.356-.144t.144-.356V9.654q0-.213-.145-.356t-.356-.144t-.356.144m3.769 0q-.144.143-.144.356v7.077q0 .212.144.356t.357.144t.356-.144t.143-.356V9.654q0-.213-.143-.356q-.144-.144-.357-.144t-.356.144m-2.912-2.913h2.769v-1.77q0-.269-.173-.442T12.769 4h-1.538q-.27 0-.442.173q-.173.173-.173.443z");
}

</style>
