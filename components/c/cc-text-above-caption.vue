<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0jst6b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e0jst6b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cc-text-above-caption" /></template>
