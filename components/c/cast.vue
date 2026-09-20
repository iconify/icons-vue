<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqjmkmb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="vqjmkmb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:cast" /></template>
