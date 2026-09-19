<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/v/v5085omnf.css';
import '../../css/w/wsbzt7bwh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkwAIXlKx"><g class="v3_i3wktz"><path class="v5085omnf"/><path class="wsbzt7bwh"/></g></mask></defs><path mask="url(#SVGkwAIXlKx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-horizontally" /></template>
