<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqjtt0biw.css';
import '../../css/u/up2-7-ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zqjtt0biw"/><path class="up2-7-ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biofuel-48" /></template>
