<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i2iz81xau.css';
import '../../css/y/ywuzefbfo.css';
import '../../css/z/zbjo2in3u.css';
import '../../css/b/brt2ttvoc.css';
import '../../css/h/h7qa06noh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i2iz81xau"/><path class="ywuzefbfo"/><path class="zbjo2in3u"/><path class="brt2ttvoc"/><path class="h7qa06noh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:crop-expand" /></template>
