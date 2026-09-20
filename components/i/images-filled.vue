<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g12y8bcqd.css';
import '../../css/h/hbnn0x-oz.css';
import '../../css/y/ylmzesbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g12y8bcqd"/><path class="hbnn0x-oz"/><path class="ylmzesbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:images-filled" /></template>
