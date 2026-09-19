<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/on1kopb6o.css';
import '../../css/n/n13l5ubmj.css';
import '../../css/x/xkitpccfs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHmrOQevo"><g class="v3_i3wktz"><path class="on1kopb6o"/><path class="n13l5ubmj"/><path class="xkitpccfs"/></g></mask></defs><path mask="url(#SVGHmrOQevo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:change-date-sort" /></template>
