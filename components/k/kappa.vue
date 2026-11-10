<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/p/psncsiz9v.css';
import '../../css/h/hjixulbzq.css';
import '../../css/a/a3525ioso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="psncsiz9v"/><path class="hjixulbzq"/><path class="a3525ioso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:kappa" /></template>
