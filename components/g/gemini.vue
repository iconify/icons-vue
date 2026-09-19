<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g41_7n8pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g41_7n8pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:gemini" /></template>
