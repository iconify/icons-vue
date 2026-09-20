<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl0qbld8c.css';
import '../../css/g/gb0t1hblg.css';
import '../../css/v/vtznphkau.css';
import '../../css/v/vz39nxhrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sl0qbld8c"/><g class="gb0t1hblg"><path class="vtznphkau"/><path class="vz39nxhrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-docker" /></template>
