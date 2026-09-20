<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/q08khjbwt.css';
import '../../css/j/jc6w6-bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q08khjbwt"/><rect transform="matrix(0 -1 -1 0 18.5 15)" class="jc6w6-bos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:center-vertical" /></template>
