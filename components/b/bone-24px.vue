<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grcycm9of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grcycm9of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bone-24px" /></template>
