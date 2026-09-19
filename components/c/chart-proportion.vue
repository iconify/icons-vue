<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kb3w1gazs.css';
import '../../css/b/b0al4ebio.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8CB7dcHl"><g class="v3_i3wktz"><path class="kb3w1gazs"/><path class="b0al4ebio"/></g></mask></defs><path mask="url(#SVG8CB7dcHl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chart-proportion" /></template>
