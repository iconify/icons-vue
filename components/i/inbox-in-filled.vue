<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/palcawbql.css';
import '../../css/g/gsx79b0zp.css';
import '../../css/e/e6h2u9bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="palcawbql"/><path class="gsx79b0zp"/><path class="e6h2u9bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:inbox-in-filled" /></template>
