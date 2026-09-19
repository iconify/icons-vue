<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypzkg3b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypzkg3b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-commit-horizontal-filled" /></template>
