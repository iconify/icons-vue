<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx89iwb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zx89iwb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:drag-handle-dots-2" /></template>
