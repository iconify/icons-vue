<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wa2i_kb9j.css';
import '../../css/a/arhdtbbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wa2i_kb9j"/><path clip-rule="evenodd" class="arhdtbbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-upload-bold-duotone" /></template>
