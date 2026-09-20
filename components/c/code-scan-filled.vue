<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cl4yuccwl.css';
import '../../css/n/nq7gkdlse.css';
import '../../css/l/lsv0mdbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cl4yuccwl"/><path class="nq7gkdlse"/><path class="lsv0mdbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:code-scan-filled" /></template>
