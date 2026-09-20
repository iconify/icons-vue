<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t_kollbbl.css';
import '../../css/d/drzavmwnq.css';
import '../../css/v/vcjdpybnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t_kollbbl"/><path class="drzavmwnq"/><path class="vcjdpybnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:accounting-invoice" /></template>
