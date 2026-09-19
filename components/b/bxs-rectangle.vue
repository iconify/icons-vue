<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cex82_b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cex82_b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-rectangle" /></template>
