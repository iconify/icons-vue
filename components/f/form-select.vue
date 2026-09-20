<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq4imsalu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4imsalu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:form-select" /></template>
