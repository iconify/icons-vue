<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5rq1-xng.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/u/uis561t1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5rq1-xng secondary"/><g class="dt0cm9dhy primary"><path class="tgy8uab8v"/><path class="uis561t1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-heart-duo" /></template>
