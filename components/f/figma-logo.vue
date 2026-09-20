<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4jai2f8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u4jai2f8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:figma-logo" /></template>
