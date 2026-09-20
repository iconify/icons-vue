<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmpwi8b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dmpwi8b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-up" /></template>
