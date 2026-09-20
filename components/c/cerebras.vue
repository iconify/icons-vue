<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzxkiu5ie.css';
import '../../css/x/xpa0b3bpk.css';
import '../../css/j/jt3_xabug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pzxkiu5ie"><path clip-rule="evenodd" class="xpa0b3bpk"/><path class="jt3_xabug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cerebras" /></template>
