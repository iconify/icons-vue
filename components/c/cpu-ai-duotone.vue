<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n7ls9qrmc.css';
import '../../css/k/kmzkjgbdi.css';
import '../../css/z/zc8qvhbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n7ls9qrmc"/><path class="kmzkjgbdi"/><path clip-rule="evenodd" class="zc8qvhbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cpu-ai-duotone" /></template>
