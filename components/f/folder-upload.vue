<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xedzjig2g.css';
import '../../css/m/mh8w0dbxt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAbbVvc7Y"><g class="v3_i3wktz"><path class="xedzjig2g"/><path class="mh8w0dbxt"/></g></mask></defs><path mask="url(#SVGAbbVvc7Y)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:folder-upload" /></template>
