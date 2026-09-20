<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezfumgw-x.css';
import '../../css/m/m66i2jztc.css';
import '../../css/e/e__fwbcqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ezfumgw-x"><path class="m66i2jztc"/><path class="e__fwbcqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:lasso-tool" /></template>
