<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4zs08s-q.css';
import '../../css/t/th4ckibjp.css';
import '../../css/u/une3fc_9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4zs08s-q"/><path class="th4ckibjp"/><path class="une3fc_9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:earth" /></template>
