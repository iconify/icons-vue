<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k1mzqdb1d.css';
import '../../css/x/xk748gddn.css';
import '../../css/y/yntq6xb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="k1mzqdb1d"/><path class="xk748gddn"/><path clip-rule="evenodd" class="yntq6xb5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:file-zip" /></template>
