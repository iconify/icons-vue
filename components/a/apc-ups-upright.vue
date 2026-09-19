<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s21x1pboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s21x1pboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apc-ups-upright" /></template>
