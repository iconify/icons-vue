<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhg495fle.css';
import '../../css/g/gb0t1hblg.css';
import '../../css/j/jje-lsbfh.css';
import '../../css/u/uslwxsbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nhg495fle"/><g class="gb0t1hblg"><path class="jje-lsbfh"/><path class="uslwxsbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cobol" /></template>
