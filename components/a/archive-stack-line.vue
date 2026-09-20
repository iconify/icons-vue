<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km-yn0bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km-yn0bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:archive-stack-line" /></template>
