<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk7-uhbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk7-uhbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-1" /></template>
