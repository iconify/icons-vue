<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moc096_4x.css';
import '../../css/h/ha-x6codx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moc096_4x"/><path class="ha-x6codx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-pie-filled" /></template>
