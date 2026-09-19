<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/lo2azab8w.css';
import '../../css/s/swzcsov6m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAOTGHdEW"><g class="v3_i3wktz"><path class="lo2azab8w"/><path class="swzcsov6m"/></g></mask></defs><path mask="url(#SVGAOTGHdEW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:blackboard" /></template>
