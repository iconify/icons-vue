<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t66zhhfyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t66zhhfyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:critical-role" /></template>
