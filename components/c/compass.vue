<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hloo9kbrj.css';
import '../../css/q/qsngmeh5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hloo9kbrj"/><path class="qsngmeh5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:compass" /></template>
