<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z576hrbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z576hrbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-vercel" /></template>
