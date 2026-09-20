<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c75-_gvco.css';
import '../../css/s/six0m6dxp.css';
import '../../css/k/kspo6_bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c75-_gvco"/><path class="six0m6dxp"/><circle class="kspo6_bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:history-2-line-duotone" /></template>
