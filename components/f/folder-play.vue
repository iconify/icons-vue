<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po9522bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po9522bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-play" /></template>
