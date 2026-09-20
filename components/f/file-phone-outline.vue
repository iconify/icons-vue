<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yghokz6by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yghokz6by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-phone-outline" /></template>
