<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deu9usb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deu9usb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:apple-news" /></template>
