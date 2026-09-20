<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/too0zm2ef.css';
import '../../css/r/rda75p-5s.css';
import '../../css/y/yzpjxzhlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="too0zm2ef"/><path class="rda75p-5s"/><path class="yzpjxzhlg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bicycle" /></template>
