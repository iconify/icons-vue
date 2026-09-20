<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhv8k2asq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhv8k2asq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:flip-v" /></template>
