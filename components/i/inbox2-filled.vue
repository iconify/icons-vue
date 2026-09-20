<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gsx79b0zp.css';
import '../../css/d/dy5yiabwz.css';
import '../../css/z/z0y52ppep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gsx79b0zp"/><path clip-rule="evenodd" class="dy5yiabwz"/><path clip-rule="evenodd" class="z0y52ppep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:inbox2-filled" /></template>
