<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox-65bbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ox-65bbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-diagonal-arrows-arrow-server-data-diagonal-internet-transfer-network" /></template>
