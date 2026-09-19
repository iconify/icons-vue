<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nldyto_pc.css';
import '../../css/a/axeioj2ci.css';
import '../../css/v/v7qis9w5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="nldyto_pc"/><path class="axeioj2ci"/><path class="v7qis9w5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:goblin" /></template>
