<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o22sjrvfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o22sjrvfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:admin-line" /></template>
