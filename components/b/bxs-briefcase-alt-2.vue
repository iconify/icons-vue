<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-6lat49e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-6lat49e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-briefcase-alt-2" /></template>
