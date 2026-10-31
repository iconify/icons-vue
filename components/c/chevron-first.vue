<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/r/rsxux02nf.css';
import '../../css/c/chfexdi1f.css';
import '../../css/b/besqxsfvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="rsxux02nf wm-k"/><path class="chfexdi1f wm-a"/><path class="besqxsfvw wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:chevron-first" /></template>
