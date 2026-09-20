<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv9ie8b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv9ie8b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrow-down" /></template>
