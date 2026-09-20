<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1k-614nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i1k-614nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-commit-outline" /></template>
