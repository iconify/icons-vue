<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vzgygcepj.css';
import '../../css/a/ay1qmvbxn.css';
import '../../css/u/un073yd9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vzgygcepj"/><path class="ay1qmvbxn"/><path clip-rule="evenodd" class="un073yd9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-square-outline" /></template>
