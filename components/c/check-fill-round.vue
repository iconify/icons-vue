<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi26zpr3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi26zpr3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:check-fill-round" /></template>
