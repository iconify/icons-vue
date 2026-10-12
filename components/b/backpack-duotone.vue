<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a1qcafbod.css';
import '../../css/l/l659m6bhj.css';
import '../../css/z/z6-1y1f0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a1qcafbod"/><path class="l659m6bhj"/><path clip-rule="evenodd" class="z6-1y1f0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:backpack-duotone" /></template>
