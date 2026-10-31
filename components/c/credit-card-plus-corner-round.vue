<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so5xjrbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so5xjrbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-plus-corner-round" /></template>
