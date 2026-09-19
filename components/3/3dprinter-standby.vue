<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx_qx2rdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx_qx2rdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:3dprinter-standby" /></template>
