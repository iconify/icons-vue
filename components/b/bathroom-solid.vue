<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zg745ongr.css';
import '../../css/x/xjtf52b4g.css';
import '../../css/e/eifg-8bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zg745ongr"/><path class="xjtf52b4g"/><path class="eifg-8bbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bathroom-solid" /></template>
