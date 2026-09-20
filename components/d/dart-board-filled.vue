<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qit1y2bjj.css';
import '../../css/m/mlq8elbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qit1y2bjj"/><path class="mlq8elbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dart-board-filled" /></template>
