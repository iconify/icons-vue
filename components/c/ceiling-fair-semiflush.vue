<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i70wu6boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i70wu6boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-fair-semiflush" /></template>
