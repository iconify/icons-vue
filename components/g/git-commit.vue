<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/v/v8n63r32y.css';
import '../../css/z/zb6ugnr2e.css';
import '../../css/e/ey9qgmrtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="v8n63r32y"/><path class="zb6ugnr2e"/><path class="ey9qgmrtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:git-commit" /></template>
