<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spajzybyt.css';
import '../../css/e/ev7zm84ma.css';
import '../../css/z/ze5omzbef.css';
import '../../css/c/c23j0pb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spajzybyt"/><g class="ev7zm84ma"><path class="ze5omzbef"/><path class="c23j0pb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-backup" /></template>
