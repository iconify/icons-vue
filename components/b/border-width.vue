<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqfk_pb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yqfk_pb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:border-width" /></template>
