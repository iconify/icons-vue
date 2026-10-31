<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3y8rb7oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3y8rb7oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-minus-round" /></template>
