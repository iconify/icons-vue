<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a6k_b7bis.css';
import '../../css/a/ao6ucc9jp.css';
import '../../css/u/uq1eecbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a6k_b7bis"/><path class="ao6ucc9jp"/><path clip-rule="evenodd" class="uq1eecbkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-left-bold-duotone" /></template>
