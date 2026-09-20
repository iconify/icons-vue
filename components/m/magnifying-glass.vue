<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc0ef1bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uc0ef1bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:magnifying-glass" /></template>
