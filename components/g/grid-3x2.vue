<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnhxq_btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnhxq_btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grid-3x2" /></template>
