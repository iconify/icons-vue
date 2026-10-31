<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/d/dc0gfbjei.css';
import '../../css/n/nntu6ub7p.css';
import '../../css/p/pkmigf6aa.css';
import '../../css/n/nfjuifbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="dc0gfbjei"/><path class="nntu6ub7p wm-shine"/><path class="pkmigf6aa wm-k"/><path class="nfjuifbiw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:coins" /></template>
