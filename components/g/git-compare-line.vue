<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7v983b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7v983b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-compare-line" /></template>
