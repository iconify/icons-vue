<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4s6whbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-front-sharp" /></template>
<style>
.u4s6whbln {
  fill: currentColor;
  d: path("m10.35 21.808l-.708-.708l1.6-1.6H6v-1h5.242l-1.6-1.6l.708-.708L13.158 19zM14 19.5v-1h4v1zm-3.77-9.27Q9.5 9.5 9.5 8.462t.73-1.769t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73M6 17V3h12v4.83h.923v3.686H18V17h-5.417l-2.233-2.233L8.117 17zm1-3.312q1.123-.517 2.472-.833q1.35-.317 2.528-.317t2.528.317t2.472.833V4H7z");
}

</style>
