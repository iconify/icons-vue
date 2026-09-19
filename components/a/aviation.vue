<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/uisjjab3n.css';
import '../../css/n/n56shgq8s.css';
import '../../css/y/y4s4b2nva.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUTP4remN"><g class="v3_i3wktz"><path class="uisjjab3n"/><path class="n56shgq8s"/><path class="y4s4b2nva"/></g></mask></defs><path mask="url(#SVGUTP4remN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:aviation" /></template>
