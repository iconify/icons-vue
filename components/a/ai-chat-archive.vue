<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en4i83-3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-chat-archive" /></template>
<style>
.en4i83-3d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 2.25H17q3.25 0 3.25 3.25v5q0 1.346-.952 2.298T17 13.75h-6.218l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H5.5q-1.346 0-2.298-.952T2.25 10.5v-5q0-1.346.952-2.298T5.5 2.25m14.875 13h-4.25q-1.875 0-1.875 1.875q0 .777.549 1.326q.097.097.201.176V20.5q0 1.75 1.75 1.75h3q1.75 0 1.75-1.75v-1.873q.104-.079.201-.176q.549-.549.549-1.326q0-1.875-1.875-1.875m-4.625 1.875q0-.375.375-.375h4.25q.375 0 .375.375t-.375.375h-4.25q-.155 0-.265-.11t-.11-.265m.75 3.375V19H20v1.5q0 .25-.25.25h-3q-.25 0-.25-.25");
}

</style>
