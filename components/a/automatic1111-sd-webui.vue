<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/sa4jm9bar.css';
import '../../css/r/r6g18ui6h.css';
import '../../css/g/g-dt7yb-t.css';
import '../../css/x/xeqhmjlyj.css';
import '../../css/a/a_vt27b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="sa4jm9bar"/><path class="r6g18ui6h"/><path class="g-dt7yb-t"/><path class="xeqhmjlyj"/><path class="a_vt27b6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:automatic1111-sd-webui" /></template>
