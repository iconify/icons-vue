<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p07tmccvv.css';
import '../../css/v/v5yammbrs.css';
import '../../css/c/cl21r6-zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="v5yammbrs"/><path class="cl21r6-zy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:import" /></template>
