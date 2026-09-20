<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y32nol_wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y32nol_wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:calculator-filled" /></template>
