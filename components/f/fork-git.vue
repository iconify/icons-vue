<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/x/xirci526l.css';
import '../../css/t/taosqkbwj.css';
import '../../css/h/hm4yo6blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="xirci526l"/><path class="taosqkbwj"/><path class="hm4yo6blt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:fork-git" /></template>
