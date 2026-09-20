<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vzgygcepj.css';
import '../../css/j/jwj5s6brs.css';
import '../../css/w/wuvczemwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vzgygcepj"/><path class="jwj5s6brs"/><path clip-rule="evenodd" class="wuvczemwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-circle-outline" /></template>
