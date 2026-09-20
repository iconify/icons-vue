<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qocb6tbrl.css';
import '../../css/q/qjh4_sbte.css';
import '../../css/a/ak1se0blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="qocb6tbrl"/><circle class="qjh4_sbte"/><path class="ak1se0blo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cookie-filled" /></template>
