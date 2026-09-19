<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8k-0xb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n8k-0xb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:automation-3p" /></template>
