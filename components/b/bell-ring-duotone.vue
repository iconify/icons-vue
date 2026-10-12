<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y0-tc4hmg.css';
import '../../css/r/rke2g1q2t.css';
import '../../css/m/m_l7ju9pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y0-tc4hmg"/><path class="rke2g1q2t"/><path class="m_l7ju9pr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-ring-duotone" /></template>
