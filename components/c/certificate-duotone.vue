<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ct1vd06xk.css';
import '../../css/y/yxy1cmbif.css';
import '../../css/l/l-hwm6t3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ct1vd06xk"/><path class="yxy1cmbif"/><path class="l-hwm6t3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:certificate-duotone" /></template>
