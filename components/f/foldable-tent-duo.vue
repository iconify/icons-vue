<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3ved-ycr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ernlo0b2m.css';
import '../../css/z/zkty8cyln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x3ved-ycr"/><g class="dt0cm9dhy primary"><path class="ernlo0b2m"/><path class="zkty8cyln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:foldable-tent-duo" /></template>
