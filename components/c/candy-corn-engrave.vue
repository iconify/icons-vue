<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jaline93j.css';
import '../../css/n/nyqj-4wfl.css';
import '../../css/d/dxfilmbdx.css';
import '../../css/a/a4vjoxyvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jaline93j wm-k"/><path class="nyqj-4wfl wm-shadow"/><path class="dxfilmbdx wm-k"/><path class="a4vjoxyvs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-corn-engrave" /></template>
