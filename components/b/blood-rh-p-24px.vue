<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cna9ecbpk.css';
import '../../css/p/pm-3j_yfg.css';
import '../../css/y/yer1a2olk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cna9ecbpk"/><path clip-rule="evenodd" class="pm-3j_yfg"/><path class="yer1a2olk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-rh-p-24px" /></template>
