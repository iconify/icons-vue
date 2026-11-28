<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az4b1ibtm.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lzukngbwu.css';
import '../../css/q/qojeivbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az4b1ibtm secondary"/><g class="dt0cm9dhy primary"><path class="lzukngbwu"/><path class="qojeivbpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:igloo-duo" /></template>
