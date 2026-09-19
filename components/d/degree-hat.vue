<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qamo9rbbx.css';
import '../../css/m/m37tbt41a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZ6jdHdfu"><g class="v3_i3wktz"><path class="qamo9rbbx"/><path class="m37tbt41a"/></g></mask></defs><path mask="url(#SVGZ6jdHdfu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:degree-hat" /></template>
