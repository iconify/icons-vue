<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb9daxbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb9daxbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loop-fill-round" /></template>
