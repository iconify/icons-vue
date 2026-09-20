<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6v7mcc5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6v7mcc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comma-circle" /></template>
