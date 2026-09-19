<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3hhdibxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s3hhdibxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-right-circle" /></template>
