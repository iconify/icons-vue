<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5he1-qhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e5he1-qhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:file" /></template>
