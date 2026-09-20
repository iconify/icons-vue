<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kodhyw0ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kodhyw0ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:donkey" /></template>
