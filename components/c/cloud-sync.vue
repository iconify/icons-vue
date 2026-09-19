<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/mnu15ok9c.css';
import '../../css/m/my73ugmzy.css';
import '../../css/w/wz2quuang.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mnu15ok9c"/><path class="my73ugmzy"/><path class="wz2quuang"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cloud-sync" /></template>
