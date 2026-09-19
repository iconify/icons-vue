<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bwpzy-b4l.css';
import '../../css/d/dk8pdv22x.css';
import '../../css/a/a6_cycxia.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGamPYc0ns"><g class="v3_i3wktz"><rect class="bwpzy-b4l"/><path class="dk8pdv22x"/><path class="a6_cycxia"/></g></mask></defs><path mask="url(#SVGamPYc0ns)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:id-card-v" /></template>
