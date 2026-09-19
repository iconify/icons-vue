<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8jbuk2hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8jbuk2hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:info-square-filled" /></template>
