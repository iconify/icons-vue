<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbz91zb-u.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tlnlkkbvm.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbz91zb-u secondary"/><g class="dt0cm9dhy primary"><path class="tlnlkkbvm"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:filter-off-duo" /></template>
