<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dtq3ihx1g.css';
import '../../css/z/zzr1xccry.css';
import '../../css/m/mat63ubej.css';
import '../../css/k/kem226bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dtq3ihx1g"/><path class="zzr1xccry"/><path class="mat63ubej"/><path class="kem226bqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cellular-network-wifi-4g" /></template>
