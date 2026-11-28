<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf3rx2bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf3rx2bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-branch-check" /></template>
