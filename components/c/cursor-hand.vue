<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f77la58rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f77la58rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cursor-hand" /></template>
