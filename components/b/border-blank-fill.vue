<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6t5y4_fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6t5y4_fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-blank-fill" /></template>
