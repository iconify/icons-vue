<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1pjvgx8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u1pjvgx8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:component-2" /></template>
