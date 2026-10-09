<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka7oo7zjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ka7oo7zjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-2-20" /></template>
