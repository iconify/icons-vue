<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/efw8ff3xu.css';
import '../../css/a/az4vgcc2z.css';
import '../../css/w/wvdhdnwxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="efw8ff3xu"/><path class="az4vgcc2z"/><path class="wvdhdnwxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jasmine" /></template>
