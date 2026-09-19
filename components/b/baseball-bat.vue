<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1yx7eixm.css';
import '../../css/z/zrcrh4bnb.css';
import '../../css/j/jxmh2ibtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="p1yx7eixm"><circle class="zrcrh4bnb"/><path class="jxmh2ibtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:baseball-bat" /></template>
