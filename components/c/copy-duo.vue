<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tbjwq7z1x.css';
import '../../css/i/i61tymsyr.css';
import '../../css/b/bzs2jobta.css';
import '../../css/v/vidyn3b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tbjwq7z1x"/><path class="i61tymsyr"/><path class="bzs2jobta"/><path class="vidyn3b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:copy-duo" /></template>
