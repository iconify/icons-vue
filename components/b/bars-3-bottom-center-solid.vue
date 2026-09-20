<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxab3-b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxab3-b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bars-3-bottom-center-solid" /></template>
