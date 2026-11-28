<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flp7q6biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flp7q6biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-down" /></template>
