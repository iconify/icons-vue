<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fahwhky7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fahwhky7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-buratto-three" /></template>
