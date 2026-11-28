<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cqp1zj20f.css';
import '../../css/g/ghgl7wbcz.css';
import '../../css/y/yoox92wcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cqp1zj20f"/><path class="ghgl7wbcz"/><path class="yoox92wcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:citrus" /></template>
