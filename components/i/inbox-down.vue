<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wqpfyoblb.css';
import '../../css/m/m0y-dcqbn.css';
import '../../css/l/lmr5zrbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqpfyoblb"/><path class="m0y-dcqbn"/><path class="lmr5zrbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:inbox-down" /></template>
