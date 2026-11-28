<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th4c8l_nb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/da92j5b5b.css';
import '../../css/q/qsgyigbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary th4c8l_nb"/><g class="dt0cm9dhy primary"><path class="da92j5b5b"/><path class="qsgyigbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-heart-duo" /></template>
