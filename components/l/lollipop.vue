<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/giai2jb9v.css';
import '../../css/d/dm7wguq1j.css';
import '../../css/m/mye-p1bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="giai2jb9v"/><path class="dm7wguq1j"/><path class="mye-p1bbs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lollipop" /></template>
