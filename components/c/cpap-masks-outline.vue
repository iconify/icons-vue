<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oso_04bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oso_04bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-masks-outline" /></template>
