<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo_5oivmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo_5oivmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-swipe-fill" /></template>
