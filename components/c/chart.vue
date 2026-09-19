<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zus-lobxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zus-lobxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:chart" /></template>
