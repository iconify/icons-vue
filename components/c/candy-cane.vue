<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5z_dxebm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g5z_dxebm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:candy-cane" /></template>
