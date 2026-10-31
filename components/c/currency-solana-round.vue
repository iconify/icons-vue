<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6oaeovhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6oaeovhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-solana-round" /></template>
