<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1n9hbhdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1n9hbhdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:floor-plan" /></template>
