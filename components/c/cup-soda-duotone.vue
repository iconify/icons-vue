<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mwl-pp3xj.css';
import '../../css/i/i-xddriwr.css';
import '../../css/b/btakn4b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mwl-pp3xj"/><path class="i-xddriwr"/><path class="btakn4b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cup-soda-duotone" /></template>
