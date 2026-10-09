<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa-dagiaz.css';
import '../../css/k/kialax5-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oa-dagiaz"/><path class="kialax5-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-network-48" /></template>
