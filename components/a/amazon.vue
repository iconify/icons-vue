<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-q5d1buo.css';
import '../../css/s/sfge3wiou.css';
import '../../css/y/y4c22ebjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f-q5d1buo"/><path clip-rule="evenodd" class="sfge3wiou"/><path class="y4c22ebjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:amazon" /></template>
