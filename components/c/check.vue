<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry1utab1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ry1utab1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:check" /></template>
