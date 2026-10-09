<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbr1am0tu.css';
import '../../css/t/tlsd_fw4s.css';
import '../../css/s/szs1icb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xbr1am0tu"/><path class="tlsd_fw4s"/><path class="szs1icb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-pie-half-48" /></template>
