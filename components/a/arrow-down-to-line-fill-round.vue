<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5yo4z6ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5yo4z6ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-to-line-fill-round" /></template>
