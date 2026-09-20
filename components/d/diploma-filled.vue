<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sam3i1beg.css';
import '../../css/a/ag59na-ob.css';
import '../../css/f/fs1zdp3zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="sam3i1beg"/><path class="ag59na-ob"/><path class="fs1zdp3zn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:diploma-filled" /></template>
