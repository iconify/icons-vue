<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezyrsyb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezyrsyb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-tune-solid" /></template>
