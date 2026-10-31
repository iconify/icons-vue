<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hgxbspbay.css';
import '../../css/i/ix_4n-b2b.css';
import '../../css/c/ccslk7bmd.css';
import '../../css/v/vfxex8bos.css';
import '../../css/u/u7l_q6bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hgxbspbay wm-k"/><path class="ix_4n-b2b wm-shine"/><path class="ccslk7bmd wm-shine"/><path class="vfxex8bos wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:file-down" /></template>
