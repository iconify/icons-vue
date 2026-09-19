<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qkvyde2_l.css';
import '../../css/h/h13c8cb6j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBM25vJeV"><g class="v3_i3wktz"><path class="qkvyde2_l"/><path class="h13c8cb6j"/></g></mask></defs><path mask="url(#SVGBM25vJeV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:check-one" /></template>
