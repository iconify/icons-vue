<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e43wavbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e43wavbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-edit" /></template>
