<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a37f418yp.css';
import '../../css/a/adjgelb-v.css';
import '../../css/m/m01tqt6ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a37f418yp"/><path class="adjgelb-v"/><path class="m01tqt6ee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cash-line" /></template>
