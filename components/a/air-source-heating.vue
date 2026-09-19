<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbl-03cst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbl-03cst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:air-source-heating" /></template>
