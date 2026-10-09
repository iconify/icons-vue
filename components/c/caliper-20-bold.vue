<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjv4dy7qr.css';
import '../../css/a/adqsiqg3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tjv4dy7qr"/><path class="adqsiqg3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caliper-20-bold" /></template>
