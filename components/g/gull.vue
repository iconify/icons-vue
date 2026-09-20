<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy3r6pbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gy3r6pbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gull" /></template>
