<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yerncn7yx.css';
import '../../css/i/i-33urxjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yerncn7yx"/><path class="i-33urxjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-left-stroke-circle-filled" /></template>
