<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvuv0ptpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvuv0ptpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hand-solid" /></template>
