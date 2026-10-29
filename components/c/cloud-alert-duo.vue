<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ls85-kd-q.css';
import '../../css/g/g56b45b0x.css';
import '../../css/c/cvilh7buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ls85-kd-q"/><path class="g56b45b0x wm-a"/><path class="cvilh7buk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-alert-duo" /></template>
