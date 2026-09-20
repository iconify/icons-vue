<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ian57fbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ian57fbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coding-apps-website-web-dev-api-cloud" /></template>
