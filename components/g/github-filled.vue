<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4c2d03ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4c2d03ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:github-filled" /></template>
