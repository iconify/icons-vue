<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/agoa3uq1m.css';
import '../../css/n/ng58zjenw.css';
import '../../css/n/n398mccnz.css';
import '../../css/g/ghrq4tbrg.css';
import '../../css/j/j9xyh0qrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="agoa3uq1m wm-k"/><path class="ng58zjenw wm-k"/><path class="n398mccnz wm-k"/><path class="ghrq4tbrg wm-shine"/><path class="j9xyh0qrv wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:egg" /></template>
