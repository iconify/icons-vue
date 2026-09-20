<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo289ibad.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qz1xfobbj.css';
import '../../css/l/l517yxbln.css';
import '../../css/b/b2uvhac7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo289ibad"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="66;0"/></path><path d="M6 2h12v0h-12ZM6 22h12v0h-12Z" class="cuyn6tgcc"><animate fill="freeze" attributeName="d" begin="0.6s" dur="0.2s" to="M6 2h12v3h-12ZM6 22h12v-3h-12Z"/></path><g stroke-dashoffset="8" class="qz1xfobbj"><path class="l517yxbln"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.9s" dur="0.2s" to="0"/></path><path class="b2uvhac7v"><animate fill="freeze" attributeName="stroke-dashoffset" begin="1.1s" dur="0.2s" to="0"/></path></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cellphonearrow-down" /></template>
