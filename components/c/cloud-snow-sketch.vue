<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/spfuxgbyh.css';
import '../../css/q/qwd_5p9df.css';
import '../../css/n/n-yhscb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="spfuxgbyh"/><path class="qwd_5p9df wm-k"/><path class="n-yhscb1g wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-snow-sketch" /></template>
