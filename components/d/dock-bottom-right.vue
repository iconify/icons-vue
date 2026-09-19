<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qubcu_soi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qubcu_soi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom-right" /></template>
