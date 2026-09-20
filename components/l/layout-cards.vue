<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3miuqtbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3miuqtbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-cards" /></template>
