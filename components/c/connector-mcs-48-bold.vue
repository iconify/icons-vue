<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiod-8bbi.css';
import '../../css/k/kq1tsebcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qiod-8bbi"/><path class="kq1tsebcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-mcs-48-bold" /></template>
