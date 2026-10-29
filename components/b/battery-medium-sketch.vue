<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/leetrzeag.css';
import '../../css/i/ih39qpbch.css';
import '../../css/y/yjgegjbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="leetrzeag wm-a"/><path class="ih39qpbch wm-k"/><path class="wm-a yjgegjbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:battery-medium-sketch" /></template>
