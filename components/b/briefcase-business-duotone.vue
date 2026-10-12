<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zg05_8bth.css';
import '../../css/g/g0m-uo1ig.css';
import '../../css/q/qp_f2rhnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zg05_8bth"/><path class="g0m-uo1ig"/><path class="qp_f2rhnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:briefcase-business-duotone" /></template>
