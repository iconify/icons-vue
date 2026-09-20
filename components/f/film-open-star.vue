<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krotz6bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krotz6bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-star" /></template>
