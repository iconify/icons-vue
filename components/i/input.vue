<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn9yuy7we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zn9yuy7we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:input" /></template>
