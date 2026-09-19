<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybx8r3b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybx8r3b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:logs" /></template>
