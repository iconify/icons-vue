<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy73lccan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy73lccan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-moon" /></template>
