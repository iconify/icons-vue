<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdxad1bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdxad1bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-30-fill" /></template>
