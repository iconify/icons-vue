<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmzn24bfh.css';
import '../../css/x/x34dybc5a.css';
import '../../css/j/jihb52b5a.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/v/vmpwdzb_y.css';
import '../../css/t/tjhblrbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wmzn24bfh"/><path class="x34dybc5a"/><path class="jihb52b5a"/><g class="jn8qy4bru"><path class="vmpwdzb_y"/><path class="tjhblrbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bowl-with-spoon" /></template>
