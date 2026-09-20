<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5bejvj0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-code" /></template>
<style>
.f5bejvj0u {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v5h-7q-2.5 0-4.25 1.75T9 19v1zm10.6 2.6L11 19l3.6-3.6l1.4 1.425L13.825 19L16 21.175zm4.8 0L18 21.175L20.175 19L18 16.825l1.4-1.425L23 19z");
}

</style>
