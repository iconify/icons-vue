<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vq2m395fl.css';
import '../../css/q/qdciwdadn.css';
import '../../css/q/qd1u16mtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vq2m395fl"/><path class="qdciwdadn"/><path class="qd1u16mtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:database-filled" /></template>
