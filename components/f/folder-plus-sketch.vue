<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oowq1xd7l.css';
import '../../css/r/ri9pveb6w.css';
import '../../css/i/i2-mb_b3z.css';
import '../../css/o/oa1gtpbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oowq1xd7l"/><path class="ri9pveb6w wm-a"/><path class="i2-mb_b3z wm-k"/><path class="oa1gtpbec wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-plus-sketch" /></template>
