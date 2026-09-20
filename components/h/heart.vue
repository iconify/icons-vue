<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cidg1bb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cidg1bb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:heart" /></template>
