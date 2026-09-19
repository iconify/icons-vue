<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xedzjig2g.css';
import '../../css/n/nbd5myb6l.css';
import '../../css/c/cpz6tmb0l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrMLoYbfG"><g class="v3_i3wktz"><path class="xedzjig2g"/><path class="nbd5myb6l"/><path class="cpz6tmb0l"/></g></mask></defs><path mask="url(#SVGrMLoYbfG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:folder-lock" /></template>
