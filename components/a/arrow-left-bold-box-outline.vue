<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vksi9_b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vksi9_b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bold-box-outline" /></template>
