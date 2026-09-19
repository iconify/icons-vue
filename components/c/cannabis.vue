<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8-1o0_1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8-1o0_1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cannabis" /></template>
