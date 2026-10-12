<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lx9cd6bvj.css';
import '../../css/e/e7e4msb7l.css';
import '../../css/v/vw068acij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lx9cd6bvj"/><path class="e7e4msb7l"/><path class="vw068acij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-metal-duotone" /></template>
