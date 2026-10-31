<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k09r7yb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k09r7yb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-fill-round" /></template>
