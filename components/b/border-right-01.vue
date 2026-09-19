<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yranhr-md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yranhr-md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-right-01" /></template>
