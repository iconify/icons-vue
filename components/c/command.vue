<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2d0jabze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2d0jabze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:command" /></template>
