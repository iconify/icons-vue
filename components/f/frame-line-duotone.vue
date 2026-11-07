<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/fg37-14pa.css';
import '../../css/b/beu8enohc.css';
import '../../css/o/oqpf2r_po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fg37-14pa"/><path class="beu8enohc"/><path class="oqpf2r_po"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:frame-line-duotone" /></template>
