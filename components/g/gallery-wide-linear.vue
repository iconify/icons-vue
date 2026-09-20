<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/icv_d8bop.css';
import '../../css/m/mqv8oacrv.css';
import '../../css/t/t5vsymb5k.css';
import '../../css/q/q3b3n4bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="icv_d8bop"/><path class="mqv8oacrv"/><circle class="t5vsymb5k"/><path class="q3b3n4bkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-wide-linear" /></template>
