<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-c3zb9h.css';
import '../../css/r/rg12uoqrx.css';
import '../../css/z/ze5omzbef.css';
import '../../css/c/c23j0pb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v7-c3zb9h"/><g class="rg12uoqrx"><path class="ze5omzbef"/><path class="c23j0pb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-temp" /></template>
