<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faa1knh-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faa1knh-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-chart-fill" /></template>
