<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gsukswb1w.css';
import '../../css/s/sxn4tfl2r.css';
import '../../css/y/yvzccrbbf.css';
import '../../css/g/gkqxq7xik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gsukswb1w"/><path class="sxn4tfl2r"/><path class="yvzccrbbf"/><path class="gkqxq7xik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:crypto-currency-bitcoin-network-globe" /></template>
