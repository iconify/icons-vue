<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb8i3i-kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb8i3i-kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:card-sd" /></template>
