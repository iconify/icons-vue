<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ofefroz8y.css';
import '../../css/k/k29p_7odf.css';
import '../../css/m/mbk-webhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ofefroz8y"/><path class="k29p_7odf"/><path class="mbk-webhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bug-play-duotone" /></template>
