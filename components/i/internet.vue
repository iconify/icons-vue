<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gkk90rbam.css';
import '../../css/h/hxzmgwzjw.css';
import '../../css/b/bognoeqpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gkk90rbam"/><path class="hxzmgwzjw"/><path clip-rule="evenodd" class="bognoeqpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:internet" /></template>
