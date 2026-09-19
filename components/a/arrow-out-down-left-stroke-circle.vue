<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-33urxjf.css';
import '../../css/y/ysrry-bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-33urxjf"/><path class="ysrry-bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-left-stroke-circle" /></template>
