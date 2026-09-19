<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bkbgjrbao.css';
import '../../css/k/k6rstmvnk.css';
import '../../css/h/hhj58fbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkbgjrbao"/><path class="k6rstmvnk"/><path class="hhj58fbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fingerprint-circled-lock" /></template>
