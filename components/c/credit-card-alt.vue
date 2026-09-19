<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5bf_zait.css';
import '../../css/r/r0ke4kbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5bf_zait"/><path class="r0ke4kbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:credit-card-alt" /></template>
