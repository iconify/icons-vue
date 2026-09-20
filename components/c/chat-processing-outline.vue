<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqp4tdvik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqp4tdvik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-processing-outline" /></template>
