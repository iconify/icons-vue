<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4q6f6bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4q6f6bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:bar" /></template>
