<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/e/ewabcgb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g transform="translate(4)" class="n1lsf0bnc"><circle class="aqhok2bbj"/><path class="ewabcgb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:figma" /></template>
