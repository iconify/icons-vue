<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l13m3w4-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l13m3w4-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:beach-ball" /></template>
