<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uc0yydbxj.css';
import '../../css/t/tcutiwbel.css';
import '../../css/r/racfkwbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uc0yydbxj"/><path class="tcutiwbel"/><path class="racfkwbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:briefcase5-filled" /></template>
