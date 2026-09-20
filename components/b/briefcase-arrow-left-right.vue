<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ml73brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ml73brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-arrow-left-right" /></template>
