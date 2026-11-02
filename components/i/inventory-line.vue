<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt4y3362k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt4y3362k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inventory-line" /></template>
