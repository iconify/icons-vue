<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txnr8nb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txnr8nb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-right-fill-round" /></template>
