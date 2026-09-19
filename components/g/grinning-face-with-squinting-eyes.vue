<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/v/vihc9mssv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVQ9zscQF"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="vihc9mssv"/></g></mask></defs><path mask="url(#SVGVQ9zscQF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:grinning-face-with-squinting-eyes" /></template>
