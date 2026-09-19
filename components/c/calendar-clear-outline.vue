<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wih274b3e.css';
import '../../css/r/rq4_dyjkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="calendar-clear-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="wih274b3e"/><path class="rq4_dyjkw"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:calendar-clear-outline" /></template>
