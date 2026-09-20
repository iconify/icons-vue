<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rz20bbcsb.css';
import '../../css/f/fu0e01bhq.css';
import '../../css/g/g6-ji5mbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rz20bbcsb"/><path class="fu0e01bhq"/><path clip-rule="evenodd" class="g6-ji5mbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alarm-remove-duotone" /></template>
