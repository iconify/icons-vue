<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kw2v_fbbh.css';
import '../../css/g/gu10zdn1y.css';
import '../../css/g/g8js9ibgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kw2v_fbbh"/><path class="gu10zdn1y"/><path class="g8js9ibgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:file-dock-duotone" /></template>
