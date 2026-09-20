<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/gw28ry-jh.css';
import '../../css/e/e1gw-kwja.css';
import '../../css/g/g5_7laczp.css';
import '../../css/g/gi8pdrn9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gw28ry-jh"/><path class="e1gw-kwja"/><path class="g5_7laczp"/><path class="gi8pdrn9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:empty-wallet-time" /></template>
