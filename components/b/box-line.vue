<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlki94r7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlki94r7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:box-line" /></template>
