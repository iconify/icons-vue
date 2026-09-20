<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/geicrrbfi.css';
import '../../css/l/lxf8azbfy.css';
import '../../css/f/f046cwqjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="geicrrbfi"/><path class="lxf8azbfy"/><path class="f046cwqjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bomb-duotone" /></template>
