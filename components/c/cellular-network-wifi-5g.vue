<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h2ebchlrj.css';
import '../../css/b/bmlc_mb5j.css';
import '../../css/h/hoic_wbnl.css';
import '../../css/k/kcfesybjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h2ebchlrj"/><path class="bmlc_mb5j"/><path class="hoic_wbnl"/><path class="kcfesybjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cellular-network-wifi-5g" /></template>
