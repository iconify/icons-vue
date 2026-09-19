<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gkya1z9sa.css';
import '../../css/f/fsbjilb4d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnuJtudBV"><g class="v3_i3wktz"><path class="gkya1z9sa"/><path class="fsbjilb4d"/></g></mask></defs><path mask="url(#SVGnuJtudBV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:circle-five-line" /></template>
