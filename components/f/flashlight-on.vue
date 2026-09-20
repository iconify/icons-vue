<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wg9lcmw6v.css';
import '../../css/c/c7vu4eb-g.css';
import '../../css/k/kbndj12cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wg9lcmw6v"/><path clip-rule="evenodd" class="c7vu4eb-g"/><path class="kbndj12cr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:flashlight-on" /></template>
