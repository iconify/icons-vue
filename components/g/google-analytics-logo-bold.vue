<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-5ei8b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-5ei8b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:google-analytics-logo-bold" /></template>
