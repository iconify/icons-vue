<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhew-98pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhew-98pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:huawei-solar-inverter" /></template>
