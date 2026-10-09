<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx2xmtbjn.css';
import '../../css/p/pbe7yvb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xx2xmtbjn"/><path class="pbe7yvb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-down-square-48" /></template>
