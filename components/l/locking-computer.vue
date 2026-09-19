<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fn--mg62j.css';
import '../../css/c/cx_xpz38m.css';
import '../../css/d/du8bscc4l.css';
import '../../css/v/vfmc-6bme.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGP4VJidAi"><g class="v3_i3wktz"><path class="fn--mg62j"/><rect class="cx_xpz38m"/><path class="du8bscc4l"/><path class="vfmc-6bme"/></g></mask></defs><path mask="url(#SVGP4VJidAi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:locking-computer" /></template>
