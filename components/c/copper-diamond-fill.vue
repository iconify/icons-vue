<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pct_djbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pct_djbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:copper-diamond-fill" /></template>
