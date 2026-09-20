<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo1y8cbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fo1y8cbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-right" /></template>
