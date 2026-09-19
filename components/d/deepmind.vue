<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir-l3d4bi.css';
import '../../css/o/od-orcbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir-l3d4bi"/><path class="od-orcbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:deepmind" /></template>
