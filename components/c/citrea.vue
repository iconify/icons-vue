<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptpn_1b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptpn_1b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:citrea" /></template>
