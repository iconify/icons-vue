<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6xsxtkuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6xsxtkuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:button-zigzag-1-bold" /></template>
