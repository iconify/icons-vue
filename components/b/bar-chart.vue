<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bexblibhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bexblibhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:bar-chart" /></template>
