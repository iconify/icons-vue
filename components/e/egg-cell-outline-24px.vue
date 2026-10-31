<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/an5k38b2g.css';
import '../../css/q/qw0bn1uiv.css';
import '../../css/c/cpg6xjbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="an5k38b2g"/><path clip-rule="evenodd" class="qw0bn1uiv"/><path clip-rule="evenodd" class="cpg6xjbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:egg-cell-outline-24px" /></template>
