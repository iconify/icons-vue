<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ymsh4jbls.css';
import '../../css/w/wqb-0n4qk.css';
import '../../css/t/t8-4j7c2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ymsh4jbls"/><path class="wm-a wqb-0n4qk"/><path class="t8-4j7c2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-duo" /></template>
