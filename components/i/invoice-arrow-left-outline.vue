<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkkze058o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkkze058o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-arrow-left-outline" /></template>
