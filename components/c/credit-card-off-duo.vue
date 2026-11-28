<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f61dg8z5p.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kn195jlxb.css';
import '../../css/e/e0m_55bwe.css';
import '../../css/o/oosjvp21t.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f61dg8z5p secondary"/><g class="dt0cm9dhy primary"><path class="kn195jlxb"/><path class="e0m_55bwe"/><path class="oosjvp21t"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:credit-card-off-duo" /></template>
