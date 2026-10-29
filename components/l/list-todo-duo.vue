<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/y5gtsacia.css';
import '../../css/b/b2_xccbks.css';
import '../../css/f/fyx95nbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wm-a y5gtsacia"/><path class="b2_xccbks"/><path class="fyx95nbgx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-todo-duo" /></template>
