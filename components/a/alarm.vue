<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sfj_64b_j.css';
import '../../css/k/kdx-xsbhx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnr1xicRM"><g class="v3_i3wktz"><path class="sfj_64b_j"/><path class="kdx-xsbhx"/></g></mask></defs><path mask="url(#SVGnr1xicRM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:alarm" /></template>
