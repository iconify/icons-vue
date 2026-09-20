<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfhjrtb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfhjrtb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-3-fill" /></template>
