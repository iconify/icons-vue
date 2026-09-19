<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sqdvfzb_i.css';
import '../../css/t/t_ev7s-sv.css';
import '../../css/b/bd3eww85q.css';
import '../../css/y/ypn7apb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVG8fzWJeXF" class="ft5dv1b6b"><path clip-rule="evenodd" class="sqdvfzb_i"/></mask><g class="ft5dv1b6b"><path class="t_ev7s-sv"/><path clip-rule="evenodd" class="bd3eww85q"/><path mask="url(#SVG8fzWJeXF)" class="ypn7apb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-24px" /></template>
