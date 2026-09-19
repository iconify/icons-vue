<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv82l7bbi.css';
import '../../css/o/ob530gbzg.css';
import '../../css/g/g8n8bnbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv82l7bbi"/><rect class="ob530gbzg"/><rect class="g8n8bnbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chart-bar-big-columns-filled" /></template>
