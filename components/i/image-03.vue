<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pd5v96lzw.css';
import '../../css/y/yopadjb1x.css';
import '../../css/j/jsn7psb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pd5v96lzw"/><circle class="yopadjb1x"/><path class="jsn7psb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-03" /></template>
