<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqfo8ifwt.css';
import '../../css/e/ef42dcbgs.css';
import '../../css/a/azuny7xti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqfo8ifwt"/><path class="ef42dcbgs"/><path class="azuny7xti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:chart-line" /></template>
