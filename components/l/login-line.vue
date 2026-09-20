<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po4qy1bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po4qy1bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:login-line" /></template>
