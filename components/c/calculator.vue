<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeo51ebfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeo51ebfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calculator" /></template>
