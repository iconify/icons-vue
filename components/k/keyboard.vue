<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bfwzw2g-y.css';
import '../../css/r/r1v4xebvh.css';
import '../../css/r/ru3v0l07s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bfwzw2g-y"/><path class="r1v4xebvh"/><path class="ru3v0l07s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:keyboard" /></template>
