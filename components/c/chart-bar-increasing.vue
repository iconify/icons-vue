<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y78neubqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y78neubqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-bar-increasing" /></template>
