<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb3zy6b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wb3zy6b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:link-none-1" /></template>
