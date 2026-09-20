<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vbhnlnbyv.css';
import '../../css/e/eztzqucpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vbhnlnbyv"/><path clip-rule="evenodd" class="eztzqucpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-bolt-minimalistic-bold-duotone" /></template>
