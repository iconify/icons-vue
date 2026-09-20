<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khq0yzb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="khq0yzb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:height" /></template>
