<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3bqpxbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3bqpxbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-right-circle" /></template>
