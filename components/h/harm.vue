<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gj7m2tbbh.css';
import '../../css/j/j7j-p3g_y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGttcsRdKb"><g class="v3_i3wktz"><path class="gj7m2tbbh"/><path class="j7j-p3g_y"/></g></mask></defs><path mask="url(#SVGttcsRdKb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:harm" /></template>
