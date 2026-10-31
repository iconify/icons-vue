<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqc1w9lyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqc1w9lyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-round" /></template>
