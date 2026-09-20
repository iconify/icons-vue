<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/izxv9-bde.css';
import '../../css/q/qz1xfobbj.css';
import '../../css/v/v9oledcij.css';
import '../../css/u/u6pv-ztpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path fill-opacity="0" class="izxv9-bde"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="66;0"/><animate fill="freeze" attributeName="fill-opacity" begin="0.9s" dur="0.15s" to=".3"/></path><path d="M6 2h12v0h-12ZM6 22h12v0h-12Z"><animate fill="freeze" attributeName="d" begin="0.6s" dur="0.2s" to="M6 2h12v3h-12ZM6 22h12v-3h-12Z"/></path></g><g stroke-dashoffset="8" class="qz1xfobbj"><path class="v9oledcij"><animate fill="freeze" attributeName="stroke-dashoffset" begin="1.15s" dur="0.2s" to="0"/></path><path class="u6pv-ztpm"><animate fill="freeze" attributeName="stroke-dashoffset" begin="1.35s" dur="0.2s" to="0"/></path></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cellphonearrow-up-twotone" /></template>
