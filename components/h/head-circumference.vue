<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd4wc4bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qd4wc4bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:head-circumference" /></template>
