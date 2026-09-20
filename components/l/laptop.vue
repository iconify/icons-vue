<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylg5d7dup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylg5d7dup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:laptop" /></template>
