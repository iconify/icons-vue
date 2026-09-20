<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/ssoo11b4a.css';
import '../../css/t/twxx0x1-g.css';
import '../../css/a/a4zn2sc5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100,"top":-33.5};
const content = `<g class="cuyn6tgcc"><path class="ssoo11b4a"/><path class="twxx0x1-g"/><path class="a4zn2sc5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lutece" /></template>
