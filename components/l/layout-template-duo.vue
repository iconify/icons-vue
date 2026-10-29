<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k9lm54fjr.css';
import '../../css/t/txj5lrrof.css';
import '../../css/c/c_w8saclo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k9lm54fjr"/><path class="txj5lrrof wm-a"/><path class="c_w8saclo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:layout-template-duo" /></template>
