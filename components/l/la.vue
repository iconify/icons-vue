<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rd8b6f9us.css';
import '../../css/g/gi_d5y8ek.css';
import '../../css/j/j0rvlxkbk.css';
import '../../css/h/hibut_iow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rd8b6f9us"/><path class="gi_d5y8ek"/><path class="j0rvlxkbk"/><path class="hibut_iow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:la" /></template>
