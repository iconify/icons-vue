<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaqzw85bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaqzw85bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:git" /></template>
