<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mj8qxfbqs.css';
import '../../css/c/ckdti6bwh.css';
import '../../css/h/h9xae-trb.css';
import '../../css/y/y1o6dws8x.css';
import '../../css/y/yerqcib8r.css';
import '../../css/s/szdxwnbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mj8qxfbqs"/><path class="ckdti6bwh"/><path class="h9xae-trb"/><path class="y1o6dws8x"/><path class="yerqcib8r"/><path class="szdxwnbim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:business-deal-handshake" /></template>
