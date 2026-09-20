<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0kuz9boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0kuz9boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-2-fill" /></template>
