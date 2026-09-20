<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sec6prbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sec6prbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:dropdown-menu" /></template>
