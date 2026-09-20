<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne6vqlbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ne6vqlbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:font-roman" /></template>
