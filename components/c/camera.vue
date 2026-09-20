<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w3xlxrjal.css';
import '../../css/a/a2by68ltf.css';
import '../../css/d/dk3bnactw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="w3xlxrjal"/><path class="a2by68ltf"/><path class="dk3bnactw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:camera" /></template>
