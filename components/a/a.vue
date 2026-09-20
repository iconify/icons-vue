<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucb6iofxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ucb6iofxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:a" /></template>
