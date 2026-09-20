<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/za2nmiyjb.css';
import '../../css/l/lzhkln8wf.css';
import '../../css/d/dscqektuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="za2nmiyjb"/><path class="lzhkln8wf"/><path class="dscqektuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cash-payment-coin-1" /></template>
