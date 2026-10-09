<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnizhvbij.css';
import '../../css/c/cbbk25b7d.css';
import '../../css/k/kwxtwsb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nnizhvbij"/><path class="cbbk25b7d"/><path class="kwxtwsb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-transport-48" /></template>
