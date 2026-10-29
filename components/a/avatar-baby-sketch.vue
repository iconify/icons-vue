<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jttxyypzl.css';
import '../../css/n/nudx0rblb.css';
import '../../css/u/uiwht6b4a.css';
import '../../css/g/ghn405o5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jttxyypzl wm-k"/><path class="nudx0rblb wm-a"/><path class="uiwht6b4a wm-k"/><path class="ghn405o5o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-baby-sketch" /></template>
