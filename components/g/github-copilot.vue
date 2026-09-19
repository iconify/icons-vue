<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu5k5fb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu5k5fb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:github-copilot" /></template>
