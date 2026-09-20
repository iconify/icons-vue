<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0m45uarn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c0m45uarn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:align-center-vertically" /></template>
