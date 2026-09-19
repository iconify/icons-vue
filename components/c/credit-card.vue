<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik48zub3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik48zub3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:credit-card" /></template>
