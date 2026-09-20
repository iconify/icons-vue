<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anudjl__q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anudjl__q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:encryption-question" /></template>
