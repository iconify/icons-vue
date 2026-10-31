<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p656s3qqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p656s3qqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-up-fill-round" /></template>
