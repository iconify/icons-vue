<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5n8go3pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="y5n8go3pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:list" /></template>
