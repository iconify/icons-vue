<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/jjfd7rbye.css';
import '../../css/f/f1r26vbpu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFEM1KGbI"><g class="v3_i3wktz"><path class="jjfd7rbye"/><path class="f1r26vbpu"/></g></mask></defs><path mask="url(#SVGFEM1KGbI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:audit" /></template>
