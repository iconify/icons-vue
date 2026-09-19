<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sy25vmbhr.css';
import '../../css/v/vvhyatv6v.css';
import '../../css/b/bp5fwubdt.css';
import '../../css/f/f10zp4qwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="sy25vmbhr"/><path clip-rule="evenodd" class="vvhyatv6v"/><path class="bp5fwubdt"/><path clip-rule="evenodd" class="f10zp4qwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hourglass-100-outline" /></template>
