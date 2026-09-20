<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zj819o97n.css';
import '../../css/l/l-stimtrd.css';
import '../../css/h/h28to3_zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect class="zj819o97n"/><path class="l-stimtrd"/><path class="h28to3_zm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:credit-card" /></template>
