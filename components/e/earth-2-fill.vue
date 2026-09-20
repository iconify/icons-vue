<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5c9j5b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5c9j5b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-2-fill" /></template>
