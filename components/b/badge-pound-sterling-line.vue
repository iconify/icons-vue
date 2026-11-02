<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka7cagbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka7cagbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-pound-sterling-line" /></template>
