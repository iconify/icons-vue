<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzj5vab1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzj5vab1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrow-down" /></template>
