<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rl0p0lbfb.css';
import '../../css/s/s91cm4bif.css';
import '../../css/z/zso2mq8uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rl0p0lbfb"/><path clip-rule="evenodd" class="s91cm4bif"/><path clip-rule="evenodd" class="zso2mq8uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:happy-24px" /></template>
