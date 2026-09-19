<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wyjaandfx.css';
import '../../css/q/qvqs3bb7l.css';
import '../../css/m/mtl7qob9c.css';
import '../../css/t/tajecub_z.css';
import '../../css/k/kottpk_wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wyjaandfx"/><path class="qvqs3bb7l"/><path clip-rule="evenodd" class="mtl7qob9c"/><path class="tajecub_z"/><path clip-rule="evenodd" class="kottpk_wd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-outline" /></template>
