<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/we0uehbyi.css';
import '../../css/k/kpsn8jbjf.css';
import '../../css/y/yq9xunb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="we0uehbyi"/><path class="kpsn8jbjf"/><path class="yq9xunb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:box-3d-three-points" /></template>
