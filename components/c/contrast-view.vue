<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bg8i-6qpe.css';
import '../../css/a/a2dqemwrc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtVNFwewy"><g class="v3_i3wktz"><path class="bg8i-6qpe"/><path class="a2dqemwrc"/></g></mask></defs><path mask="url(#SVGtVNFwewy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:contrast-view" /></template>
