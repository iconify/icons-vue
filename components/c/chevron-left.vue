<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg42bkbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg42bkbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-left" /></template>
