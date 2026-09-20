<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7f-e8tjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7f-e8tjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-bold-outline" /></template>
