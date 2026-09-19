<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kaxlnzbpc.css';
import '../../css/s/sjprw7bfy.css';
import '../../css/n/ngc_fgbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kaxlnzbpc"/><path clip-rule="evenodd" class="sjprw7bfy"/><path class="ngc_fgbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ambulance-outline-24px" /></template>
