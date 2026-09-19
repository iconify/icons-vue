<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqa3tkb1n.css';
import '../../css/g/go62nyfcr.css';
import '../../css/k/k91suv-ws.css';
import '../../css/i/icsy_rbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="go62nyfcr"/><path class="k91suv-ws"/><path class="icsy_rbek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:calendar-minus-solid" /></template>
