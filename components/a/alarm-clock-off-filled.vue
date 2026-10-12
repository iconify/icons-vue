<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4g99_bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4g99_bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:alarm-clock-off-filled" /></template>
