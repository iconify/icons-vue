<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvsdzhbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvsdzhbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:credit-card" /></template>
