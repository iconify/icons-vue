<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6_mqv_xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6_mqv_xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:glc" /></template>
