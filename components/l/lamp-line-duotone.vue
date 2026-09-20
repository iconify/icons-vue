<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ick8o1b-y.css';
import '../../css/d/d1ue3bczq.css';
import '../../css/k/ksw3aymwa.css';
import '../../css/e/e9h1t6b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ick8o1b-y"/><path class="d1ue3bczq"/><path class="ksw3aymwa"/><path class="e9h1t6b7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lamp-line-duotone" /></template>
