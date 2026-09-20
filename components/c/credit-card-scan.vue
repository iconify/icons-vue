<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs6y6vbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs6y6vbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:credit-card-scan" /></template>
