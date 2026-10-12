<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z3bjef6ae.css';
import '../../css/o/o58l7acvc.css';
import '../../css/t/tupglrb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z3bjef6ae"/><path class="o58l7acvc"/><path class="tupglrb1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:award-duotone" /></template>
