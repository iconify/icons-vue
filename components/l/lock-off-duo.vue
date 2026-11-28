<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8qn0jbck.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m0psnqe2o.css';
import '../../css/h/hgj93qb8m.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8qn0jbck secondary"/><g class="dt0cm9dhy primary"><path class="m0psnqe2o"/><path class="hgj93qb8m"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lock-off-duo" /></template>
