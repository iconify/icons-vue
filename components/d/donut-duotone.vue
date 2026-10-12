<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wnj3n4b3q.css';
import '../../css/j/jufq728bv.css';
import '../../css/f/f29fwjbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wnj3n4b3q"/><path class="jufq728bv"/><path class="f29fwjbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:donut-duotone" /></template>
