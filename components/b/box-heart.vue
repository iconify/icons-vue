<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9rlgb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb9rlgb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:box-heart" /></template>
