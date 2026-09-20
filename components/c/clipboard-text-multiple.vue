<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txum_rt2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txum_rt2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-text-multiple" /></template>
