<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/a5-jzac4o.css';
import '../../css/h/hppj8jbqh.css';
import '../../css/y/yknmznb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a5-jzac4o"/><path class="hppj8jbqh"/><path class="yknmznb5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:files" /></template>
