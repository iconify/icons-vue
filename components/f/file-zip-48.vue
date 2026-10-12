<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_z99bhx.css';
import '../../css/c/ck6_3u-qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="ck6_3u-qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-zip-48" /></template>
