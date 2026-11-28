<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4w8drb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4w8drb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:git-commit-x" /></template>
