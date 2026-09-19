<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/g4iz8vbbj.css';
import '../../css/x/xoigmefmm.css';
import '../../css/w/wj--2_bna.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGG6iAxo0v"><g class="v3_i3wktz"><path class="g4iz8vbbj"/><path class="xoigmefmm"/><path class="wj--2_bna"/></g></mask></defs><path mask="url(#SVGG6iAxo0v)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:land-surveying" /></template>
