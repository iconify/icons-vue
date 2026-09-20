<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kutuzrblr.css';
import '../../css/h/hz7_q3dyh.css';
import '../../css/p/pn5m_ac8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kutuzrblr"/><path class="hz7_q3dyh"/><path class="pn5m_ac8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-pull-request-draft-sharp-fill" /></template>
