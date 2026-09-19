<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvvoo3bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvvoo3bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-commit-horizontal" /></template>
