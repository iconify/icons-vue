<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q73u62rwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q73u62rwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:indent-decrease" /></template>
