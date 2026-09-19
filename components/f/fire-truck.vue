<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy6mcej6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yy6mcej6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fire-truck" /></template>
