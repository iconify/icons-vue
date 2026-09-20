<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p07tmccvv.css';
import '../../css/c/cy28a8b1v.css';
import '../../css/j/jr92re-vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="cy28a8b1v"/><path class="jr92re-vr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flip-to-back" /></template>
