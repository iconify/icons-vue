<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n71xjbcbt.css';
import '../../css/q/qbmgmeber.css';
import '../../css/k/k0b7xsfel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n71xjbcbt"/><path clip-rule="evenodd" class="qbmgmeber"/><path class="k0b7xsfel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cup-music-filled" /></template>
