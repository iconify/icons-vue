<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yx7awmbxt.css';
import '../../css/t/tworh6b6a.css';
import '../../css/s/sqise2bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wm-k yx7awmbxt"/><path class="tworh6b6a wm-shine"/><path class="sqise2bpb wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:avatar-bear" /></template>
