<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvz4xhbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvz4xhbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bookmark-check-filled" /></template>
