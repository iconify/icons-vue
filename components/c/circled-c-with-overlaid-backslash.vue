<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_weg3b7j.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/d/d0bf9jbax.css';
import '../../css/g/goyqnobna.css';
import '../../css/r/reogukpic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="j_weg3b7j"/><g class="sxsjrzbyv"><path clip-rule="evenodd" class="d0bf9jbax"/><circle class="goyqnobna"/><path class="reogukpic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:circled-c-with-overlaid-backslash" /></template>
