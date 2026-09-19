<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/iuct5_bce.css';
import '../../css/p/p9swojy5o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<mask id="svgIDa"><g class="v3_i3wktz"><path class="iuct5_bce"/><path class="p9swojy5o"/></g></mask><path mask="url(#svgIDa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:list-two" /></template>
