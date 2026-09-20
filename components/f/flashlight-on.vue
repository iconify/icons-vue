<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx6kxve6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flashlight-on" /></template>
<style>
.qx6kxve6f {
  fill: currentColor;
  d: path("M7 5.5V3h10v2.5zm5.707 9.209q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291M9 21V10.692l-2-3V6.5h10v1.192l-2 3V21z");
}

</style>
