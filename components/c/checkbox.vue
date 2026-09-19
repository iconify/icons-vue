<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/p/p-3d8dotc.css';
import '../../css/q/qwhezwbdq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGU9WF5dmC"><g class="v1_swcb_o"><path class="p-3d8dotc"/><path class="qwhezwbdq"/></g></mask></defs><path mask="url(#SVGU9WF5dmC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:checkbox" /></template>
