<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuy-08beb.css';
import '../../css/j/j3xt6_l2d.css';
import '../../css/m/m93r1pbqy.css';
import '../../css/m/macilbcnn.css';
import '../../css/z/zsqz4clcq.css';
import '../../css/t/ttcuutlmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tuy-08beb"/><path class="j3xt6_l2d"/><path class="m93r1pbqy"/><path class="macilbcnn"/><path class="zsqz4clcq"/><path class="ttcuutlmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-game-controller-b-outline" /></template>
