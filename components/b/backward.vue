<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t38e9cb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="t38e9cb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:backward" /></template>
