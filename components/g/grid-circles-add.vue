<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/w/w56pzz2bw.css';
import '../../css/g/gz7pzxb9g.css';
import '../../css/j/jf5hngtdr.css';
import '../../css/a/a-yjgsg3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><circle class="w56pzz2bw"/><circle class="gz7pzxb9g"/><circle class="jf5hngtdr"/><path class="a-yjgsg3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:grid-circles-add" /></template>
