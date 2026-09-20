<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i714gtksb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i714gtksb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:face" /></template>
