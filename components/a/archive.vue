<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wgxujor3o.css';
import '../../css/g/grrd1nb3v.css';
import '../../css/r/r_40qrwdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wgxujor3o wm-k"/><path class="grrd1nb3v wm-shine"/><path class="r_40qrwdi wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:archive" /></template>
