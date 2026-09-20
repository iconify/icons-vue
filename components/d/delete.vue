<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8n0i6b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i8n0i6b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:delete" /></template>
