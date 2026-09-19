<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/qgajy22ee.css';
import '../../css/f/fxn-nbfom.css';
import '../../css/v/vac8d1bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qgajy22ee"/><path class="fxn-nbfom"/><path class="vac8d1bao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:basketball-alt" /></template>
