<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gej5qbeik.css';
import '../../css/w/w76yeublj.css';
import '../../css/z/zxu7hye5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="gej5qbeik"><path class="w76yeublj"/><path class="zxu7hye5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:adobe-xd" /></template>
