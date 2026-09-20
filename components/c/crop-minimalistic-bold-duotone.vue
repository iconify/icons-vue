<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ynvhk2btp.css';
import '../../css/q/qn6zfg6br.css';
import '../../css/g/g0c5c7u0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ynvhk2btp"/><path class="qn6zfg6br"/><path class="g0c5c7u0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crop-minimalistic-bold-duotone" /></template>
