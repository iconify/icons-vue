<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zo0jdhbwq.css';
import '../../css/d/dgi3ajoxw.css';
import '../../css/f/feccq4bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zo0jdhbwq"/><path class="dgi3ajoxw"/><path class="feccq4bff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ipod" /></template>
