<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hj4zhi7dw.css';
import '../../css/r/rublczxpb.css';
import '../../css/h/h7cjiyxej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hj4zhi7dw"/><path class="rublczxpb"/><path class="h7cjiyxej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-unread-bold-duotone" /></template>
