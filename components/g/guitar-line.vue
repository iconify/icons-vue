<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut-rukwjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut-rukwjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:guitar-line" /></template>
