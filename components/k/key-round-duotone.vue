<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l2ag24bhm.css';
import '../../css/v/vsu8o2e_j.css';
import '../../css/q/qj4n1fmer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l2ag24bhm"/><path class="vsu8o2e_j"/><path class="qj4n1fmer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:key-round-duotone" /></template>
