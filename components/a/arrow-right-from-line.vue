<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idq7gnb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idq7gnb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-right-from-line" /></template>
