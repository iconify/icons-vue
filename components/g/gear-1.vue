<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gtyn32zwx.css';
import '../../css/c/cjzjnwcsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gtyn32zwx"/><path class="cjzjnwcsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:gear-1" /></template>
