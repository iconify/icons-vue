<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0tfvsbut.css';
import '../../css/q/qc7bzg-vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0tfvsbut"/><path class="qc7bzg-vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:history" /></template>
