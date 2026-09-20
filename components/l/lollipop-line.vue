<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8cj_hf4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8cj_hf4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lollipop-line" /></template>
