<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c42-7gvoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c42-7gvoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:globe" /></template>
