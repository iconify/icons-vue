<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vgovwzbmp.css';
import '../../css/o/oycv71bfr.css';
import '../../css/r/rxp-h_bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vgovwzbmp"/><path class="oycv71bfr wm-a"/><path class="rxp-h_bzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:code-xml" /></template>
