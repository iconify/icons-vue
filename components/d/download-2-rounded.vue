<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-e38mstk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:download-2-rounded" /></template>
<style>
.c-e38mstk {
  fill: currentColor;
  d: path("M5.5 20h13q.213 0 .356.144t.144.357t-.144.356T18.5 21h-13q-.213 0-.356-.144T5 20.499t.144-.356T5.5 20m6.13-3.379q-.164-.08-.295-.242l-3.989-5.292q-.298-.404-.077-.851t.723-.447h1.643V3.808q0-.343.232-.576T10.442 3h3.097q.343 0 .575.232t.232.576v5.98h1.643q.502 0 .723.448q.22.447-.077.85l-4.008 5.293q-.122.161-.294.242q-.173.081-.356.081t-.347-.08");
}

</style>
