<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikvrw9kzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikvrw9kzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-search" /></template>
