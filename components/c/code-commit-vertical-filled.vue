<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhn23_shf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhn23_shf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-commit-vertical-filled" /></template>
