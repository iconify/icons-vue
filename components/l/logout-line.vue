<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlqj5_bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlqj5_bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:logout-line" /></template>
