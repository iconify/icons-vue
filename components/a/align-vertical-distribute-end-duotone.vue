<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qbo0_6b1y.css';
import '../../css/g/g9nxjlb6k.css';
import '../../css/c/cm2jootob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qbo0_6b1y"/><path class="g9nxjlb6k"/><path class="cm2jootob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-distribute-end-duotone" /></template>
