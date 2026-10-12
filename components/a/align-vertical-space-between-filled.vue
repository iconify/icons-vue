<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv5jycdoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv5jycdoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-space-between-filled" /></template>
