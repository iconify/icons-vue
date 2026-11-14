<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otuoxrpac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:call-voice-chat" /></template>
<style>
.otuoxrpac {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm4 3q.561 0 1.28.72q.161.16.205.383l.25 1.25q.015.073.015.147q0 .811-.47 1.28q-.09.091-.206.146q.309.441.75.75q.055-.116.146-.206q.469-.47 1.28-.47q.074 0 .147.015l1.25.25q.223.044.383.205q.72.719.72 1.28v1.25q0 1.5-1.5 1.5q-2.936 0-4.968-2.032T7.75 7.25q0-1.5 1.5-1.5z");
}

</style>
