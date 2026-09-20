<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wjuoup6qs.css';
import '../../css/t/tazr0wunn.css';
import '../../css/j/j16pcib4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjuoup6qs"/><path class="tazr0wunn"/><path class="j16pcib4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:convert-three-d-cube" /></template>
