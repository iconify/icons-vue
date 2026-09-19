<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyji3vb3h.css';
import '../../css/b/b3dn0_1qr.css';
import '../../css/e/e1a212beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="nyji3vb3h"><path class="b3dn0_1qr"/><path class="e1a212beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:canva" /></template>
